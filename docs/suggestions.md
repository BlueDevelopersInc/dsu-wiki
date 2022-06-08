# Suggestions System

First, you need to configure suggestions. 

## How to configure

### Enable Suggestions

in the suggestions.yml.. switch enabled to true
```yaml
enabled: true
```

### Set suggestions channel

in the suggestions.yml, set suggestions_channel to your suggestions channel

```yaml
enabled: true
suggestions_channel: 894677242238623796 #Example ID, this won't work for you
```

### Other configuration

Set messages, toggle things, until it is ready to be used

## How it works


### Make suggestion
The user uses the `/suggest <Suggestion>` command, a new message will be sent in the suggestions channel.. including a Suggestion Number.

### Add a note

Add a note to tell your user some note about the suggestion. use `/addnote <Suggestion Number> <Note Text>` to add note.. Requires Admin in admin list
As soon as you add it, last one made will be displayed on the suggestion

### Approve or deny the suggestion

use `/approve <Suggestion Number>` or `/deny <Suggestion Number>` to approve or deny
Also requires Admin in admins list


## Example final look

![img](https://discordsrvutils.xyz/img/features/Feature-8.png) 

You can modify this in config

### Note
Do not modify the database or break the system



