---
script: S01
location: church
target: priest
---
# priest_start
trigger: click
- priest: God bless you.
- character + priest

# presenting_to_priest
trigger: present
- priest: Only God has the answer.
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: priest
- priest: I'm a priest.
