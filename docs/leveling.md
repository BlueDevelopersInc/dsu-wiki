# Leveling

DiscordSRVUtils has its own leveling system. This System works like a lot other plugins but with some changes

## How it works

Just like a normal leveling plugin. Every Minecraft Player has his own leveling system. But as soon as they link their account, Their Discord User shares the level and xp. Chatting in discord would also increase their XP.

!!! note
    A Player level up **15-25** xp each time they send a message.

## XP System
This plugin uses the same algorithm mee6 uses, which means that the more the player level up, the more xp is required to levelup to the next level. The Algorithm used to calculate level's xp is `5 * (lvl ^ 2) + (50 * lvl) + 100 - xp` where lvl is current level, and xp is how much xp you already have towards next level.

## Anti Spam

If this option is enabled in config, every player can only levelup in xp 1 time per minute.