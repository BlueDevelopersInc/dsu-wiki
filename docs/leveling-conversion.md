# Leveling Major Changes

Two Major changes were made to the leveling system: 

1. Mee6 aligorithm implemented
2. Leveling roles was changed to leveling rewards


## Mee6 aligorithm implemented

Previously, a player needed 300xp to levelup to the next level, which made it very easy to reach level 100 and even 200, so a change had to be made. Now, after DiscordSRVUtils 1.2.11 Build **#186** (or release 1.2.11) Instead of 300 xp each level has it's own xp requirements, to make it harder to level up each time.

This means that people who were level 25, should be level 12 with the new mee6 aligorithm, and people with level 100 would be alot less, and so on.

### To Convert
To keep it all fair for new and old players, you can convert old leveling to new one, this is done by calculating total xp they ever had since every level required 300 xp only, you can do this by the following command **in console** `dsu migrateleveling` 1 time in console, this should be executed ASAP! Because players would start to get more than 300xp which would cause less fairness every moment you wait, you can upload the update and restart and put the command in console while it's starting and it will do it when server finishes starting.

!!! info
    You can reset everyone'e level by using the `/dsu resetlevel all` command.

## Leveling roles -> Leveling Rewards

Previously, it was only possible to give players rewards of their active chatting by just discord roles, now they can be multiple roles + console command, by updating the plugin the old format is converted to the new format and renamed to `leveling-rewards.json` but that doesn't mean not to touch it, you still need to adjust levels to the **new mee6 aligorithm** (if you previously assumed level 100, now it takes up to 5 months of active chatting to reach that level). For full documentation on how to use the new format, check [here](leveling-rewards.md)


