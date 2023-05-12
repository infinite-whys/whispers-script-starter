---
script: S01
location: mine
---
# foreman_start
trigger: click
target: foreman
- foreman: I'm the foreman of this mine, and I gotta get these lazy bums back to work!
- character + foreman

# presenting_to_foreman
target: foreman
trigger: present
- foreman: As if I got time to look at your crap.
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: foreman
- foreman: I'm the foreman of the mine.

# miner_start
trigger: click
target: miner
- miner: Howdy, name's Henry. I'm the mine's safety steward, or busybody as the foreman calls me.
- character + miner

# presenting_to_miner
target: miner
trigger: present
- miner: Sorry partner, can't help you there.
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: miner
- miner: I'm a miner.
