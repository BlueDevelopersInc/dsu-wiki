# Leveling Rewards

You can control the leveling rewards rewards in the `/plugins/DiscordSRVUtils/leveling-rewards.json` file, this file is usually empty by default but 
here we will explain how to use it

# Format
It's a json, key is the level value is an object, that contains console commands or discord role ids, here is how to use it:

```json
{
  "3": {
    "roles": [1, 2, 3, 4]
  },
  "10": {
    "roles": [5, 6, 7, 8]
  },
  "20": {
    "roles": [9, 10, 11, 12],
    "commands": ["give [stats.name] diamond 32", "eco give [stats.name] 10000"]
  }
}
```

In the previous json when user level up to level 3 they get roles with ids 1, 2, 3, 4 (until they reach the next level with roles setup) and in level 20 they receive 32 diamonds in game and 10,000$ in game.

!!! tip
    Player gets their reward when they join if they were offline during levelup (leveled from discord)

!!! info
    The previous `leveling-roles.json` will automatically be converted to the new format if you used it, but you might want to edit it due to the implementation of mee6 leveling

