---
location: blacksmiths
script: S01
target: blacksmith
---
# blacksmith_start
trigger: click

- blacksmith: ...
- character + blacksmith

# presenting_to_blacksmith
trigger: present

- blacksmith: ...
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: blacksmith
- blacksmith: I'm a blacksmith.
