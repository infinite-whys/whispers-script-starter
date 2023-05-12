---
script: S01
location: saloon
target: bartender
---

# bartender_start
trigger: click
target: bartender
- bartender: What would you like to order? 
- character + bartender

# presenting_to_bartender
trigger: present
target: bartender

- bartender: Sorry, I just need to take care of the customers, if you don't mind.
---
//present: lockpick
//---
//present: badge
//---
//present: gun
//---
//present: forensics_handbook
//---

present: beer
- bartender: Do you like your beer?
