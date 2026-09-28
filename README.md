# I-am-doing-terrible-things-to-DoomRPG
as per the title. A personal fork of DRPGRLAX for Phase Sisters vs Twitch Chat.

The ultimate goal is to have a massively shaved down DRPG without the RPG elements, but keeping some of the really good stuff, including the whole-ass outpost and arenas, the shop and locker functions, the stage select, the gambling minigame and loot drops, literally only one skill (transport), the many DRPG powerups, the whole health storing system (in stats.c btw), and the assembly machine that is part of DRPGRLA. 

Currently I have gutted the menu down to a small number of selections, removed augs, stims, turrets, status effects, toxicity, a few of the level and rank trackers, messed a bit with the shop and for the most part found a few of the weirder interactions.

The current hurdle that I'm way too stupid to work out is how to detach ALL the stats from both enemies and player, as functions like drops, health, movement, ammo amounts and damage to enemies and player, are all intrinsically linked to the them, which require level ups to make better, both the enemies and the player, which has been partially gutted in the sense that it doesn't matter (though it means enemies do not drop loot).

I also really want to have DRLAX logic dictate the world drops and such more than DRPG, as DRPG tends to be a bit stingy. The popping back to the outpost between stages and the shopping and loot will provide good downtime activities for chat and myself to detox during the events, hopefully with a fully custom outpost down the line.
