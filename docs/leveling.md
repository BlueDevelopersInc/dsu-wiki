# Leveling

DiscordSRVUtils has its own leveling system. This System works like a lot other plugins but with some changes

## How it works

When a player chat in minecraft, they are given **15-25** xp, if the xp reaches maximum for the current level, they levelup to the next level. If the player link their discord account, when they chat on discord, it will also add xp to their minecraft account. This system depends only on chatting, minecraft xp/level system is not involved.

!!! info 
    When using anti-spam (enabled by default) xp will only be added 1 time per minute.

## XP System
This plugin uses the same algorithm mee6 uses, which means that the more the player level up, the more xp is required to levelup to the next level. The Algorithm used to calculate level's xp is `5 * (lvl ^ 2) + (50 * lvl) + 100 - xp` where lvl is current level, and xp is how much xp you already have towards next level.

## Anti Spam

If this option is enabled in config, every player can only levelup in xp 1 time per minute.