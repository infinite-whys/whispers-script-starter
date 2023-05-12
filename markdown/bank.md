---
location: bank
script: S01
target: banker
---
# banker_start
trigger: click
- banker: How can I help?
- character + banker

# presenting_to_banker
trigger: present
- banker: Sorry partner, can't help you there.
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: banker
- banker: I'm a banker.
