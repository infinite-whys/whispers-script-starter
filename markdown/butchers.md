---
script: S01
location: butchers
target: butcher
---

# butcher_start
trigger: click

- butcher: Howdy! Betsy the butcher at your service.
- character + butcher

# presenting_to_butcher
trigger: present

- butcher: Sorry partner, can't help you there.
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: butcher
- butcher: You want to know about me?
