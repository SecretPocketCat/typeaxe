# Design notes

## Mining

### Games to check

- Dome Keeper - mining part of the loop
  - this one is the most interesting to me
  - the pacing works really well - makes backtracking with resources more interesting
  - the upgrades are fun
- Steamworld Dig/2
  - Traversal: platforming instead of levitating is fun
    - that adds upgrade options for platforming
    - a jetpack upgrade might be an option
    - wall jumping is super important if the player should backtrack with resources
  - big mining upgrades are great (1 hits for what was 3 hits before the upgrade etc.)
  - mining above the player works, but for just one tile (can't mine while jumping)
- Mining Mechs (demo or full release - it's just 3€ anyway)
  - having multiple different mining limits/capacities (dirt + the actual minerals) is kinda annoying
  - shiny things are nice, but they must be rare
  - waiting for long animations (eg. payout) is annoying
  - having layers/levels/difficulties/progression is great, but it shouldn't be too grindy
  - travelling back up is kinda boring - it should be motivated by smt. (like in Dome Keeper)
- Super Motherload
  - chains (drilling/mining) in a line is fun
    - could lead to a combo
  - gravity is an interesting limitation (can't drill up)
  - resource combo - drilling a bunch of the same resource in line
  - some limiting factor(s) like capacity (how much the player can carry), time (oxygen) below etc.
  - the hull damage system is kinda annoying (smashing into wall causes dmg and the player can die and lose resources)
- Wall World
- Forager (for juice) - just watch vids

### Juice

- slight screenshake on each char
- the mined block should react
  - shake
  - deform/scale
  - tiny shockwave?
- the tween/animation should be very fast and scalable (basically hit almost immediately and the rest is just the tool tweening out)
  - ideally could be layered so that fast typers just get more tools used and it doesn't look weird

### Notes/Ideas
