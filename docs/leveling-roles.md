# Leveling Roles

You can control the leveling role rewards in the `/plugins/DiscordSRVUtils/leveling-roles.json` file, this file is usually empty by default but 
here we will explain how to use it

# Format
it's a json, key is the level value is the role id, here is an example

```json
{
  "3": 1,
  "10": 2,
  "20": 3
}
```

In the previous json, 1, 2 and 3 must be replaced with an actual role id, don't forget!

# How it works
User only gets 1 leveling role maximum, if you use the json above (and replaced ids), here are the conditions:

If you are level 0->2 you get no roles, 3->9 role `1`, if they reach level 10 role `1` gets removed and it is replaced with role `2`, until you reach level
20, and then you get role `3` (and the role `2` is removed) and this role won't get removed.