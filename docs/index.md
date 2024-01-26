# Welcome to DiscordSRVUtils Wiki!

We work hard to make the plugin very easy as we can. Here we explain how to do everything, and anyway everything is easy!

# How to install
1. Download [DiscordSRV Plugin](https://modrinth.com/plugin/discordsrv) and drop it into your plugins folder
2. Restart your server, and follow the DiscordSRV Installation steps
3. Drop [DiscordSRVUtils](https://modrinth.com/plugin/discordsrvutils) into your plugins folder
4. Configure the plugin, in most cases you need to have admin

# How to get Admin
Its very simply, before the steps make sure developer mode is on:

![img](images/enable-dev-mode.gif)

1. Go into your `config.yml` of DiscordSRVUtils
2. Add your user/role ID as shown below
3. Reload the plugin using `/dsu reload` and make sure you have the permission `discordsrvutils.reload` 

```yaml
admins: [831970480499589220]
```

!!! warning
    Whoever is in this list or has a role that is in this list has access to **all** discord commands from this plugin.

# How to Disable Discord Commands

1. Go to `config.yml`
2. Scroll until you find `disabled-commands`, add commands you want to disable
3. Reload the plugin using `/dsu reload` and make sure you have the permission `discordsrvutils.reload`  

```yaml
disabled-commands: [help]
```

  
!!! info 
    It will be removed from slash command list, those commands disabled will be as if they don't exist

!!! warning
    Please do not use aliases. They aren't supported.

# Requirements

- DiscordSRV 1.27.0+.
- Bukkit/Spigot/Paper (1.8+)

# Optional Permissions

- Ban Members (for punishment sync)
- Manage Server (for detecting invititers)
- Manage Channels (for ticket creation)
- Manage Roles (for welcomer role, and syncing mutes and ban role)

# How we store data

In a local database by default, or mysql if you configure it to.


