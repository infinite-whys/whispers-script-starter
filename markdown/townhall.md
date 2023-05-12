---
script: S01
location: townhall
target: mayor
---
# mayor_start
trigger: click
- mayor: Time is money. Come on. Chop chop.
- character + mayor

# presenting_to_mayor
trigger: present

- mayor: Sorry partner, can't help you there.
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
- mayor: Mr Clayton is an asset to the local economy, and a tireless contributor to my and my associates' passive income.
