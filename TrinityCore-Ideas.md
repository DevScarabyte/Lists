### TrinityCore Random Ideas

- [ ] adump
- [ ] tele instanceid
- [ ] tele name <player> npc(gu)id <gu/id>
- [ ] quest requirements
- [ ] wp modify orientation
- [ ] wp modify posx/y/z
- [ ] additem <itemid> <player id/name>
- [ ] gdump
- [ ] list tokens
- [ ] ainfo
- [ ] loot
- [ ] mod xp
- [ ] lookup friendlist
- [ ] guild log <bank/event>
- [ ] arena session change
- [ ] lookup player onlineip
- [ ] lookup area <id>

### These are from the forum post will clean up when i can.

Allow parameter to onlinelist to allow choice map/zone, add country, names of maps, zones with for example onlinelistextended. Ie: account onlinelist map 0.

tele instanceid (or iid) to allow gm to teleport a selected instance id (ie to fix problems of teleportation to some heroic instances/raids without having to unbind.
tele name <player> npcid / npcguid <id/guid>

Allow every command with time as parameter to choice the time type ie: seconds, hours, days.
adump (account dump).

A command to check if a player fits the requirements of one quest (have all items and where (on player, on bank), killed all mobs, etc) and location of quest taker.

Allow .additem to ignore the unique flag to get 1 unique item on inventory.

Add .wp modify orientation .wp modify posx/y/z commands.

Allow .additem to set player if isnt targeted for example .additem <item id> <player id/player name>

A command to dump a whole guild and restore with all the members and bank items, if items are somewhere else write where they are (to restore defaced guilds)

a command to list the amount of tokens one character owns.

ainfo, account info, adds the last ips one account used, creation date, email, number of characters, level, class, gold, location, rename from lookup player account/ip/email.

debug loot command, to allow gm to see the loot one mob generated if you are unable to loot the mob because some strange reason (ie keltzuzad failing to give loot).

mod xp command to allow gm to reward the xp of one quest after core crash. Thx Guybrush.

a command to allow gms to see friendlist of someone and who have someone on friendlist, ignore and who have it on ignore.

create a gm command to allow to read guild_eventlog and guild_bank_eventlog without having to join guild.

create a command for automatic arena session change.

lookup player onlineip search for players with specific ip.

lookup area id command, to allow to search area names.
