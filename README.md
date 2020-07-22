# GhostSpectator
Players become tutorial, instead of spectator, when they are dead. They cannot interact with most items of the map (lifts, doors, intercom). 
They are visible and can talk to others (the problem is in smod, it is no longer possible to turn on ghost mode)
They cannot pickup items or drop them.
When a ghost drops a coin, he is teleported to random player.
Don't worry, tutorials can respawn.

# Configs 

If ghosts should not interact with doors or elevators

`gs_block_doors_for_ghosts: true`

Broadcast, that Ghosts get on spawn

`gs_spawn_broadcast: <size=40>You've been spawned as a <color=#9E9E9E>Ghost</color>! \n Drop the <color=#ABFDFF>coin</color> to teleport to random <color=green>player</color>.</size> <size=25>\n You <color=red>cannot</color> pickup or drop <color=lime>items</color>. \n You <color=red>cannot</color> interact with <color=#FFFA5A>doors</color> or <color=#FFFA5A>elevators</color>. \n You <color=lime>can</color> talk to others. \n You will <color=lime>respawn</color> soon.</size>`

Time of broadcast, that ghosts get on spawn

`gs_spawn_broadcast_time: 20`


# Issues
When Ghost is killed by 049, he will become zombie after 6 seconds. No recall needed. Either way, they could not become zombie at all.
Ghosts can start 914, but not change it's mode
I cannot make them invisible due to it is problem of Smod, they did not add ghost mode, it is broken.
