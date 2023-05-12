---
script: S01
location: square
target: zeed
---
# zeed_start
trigger: click
target: zeed

- zeed: Oh, uhh, h-hello! How can I help you?
- character + zeed

# presenting_to_zeed
trigger: present
target: zeed
- zeed: Sorry, I really don't know that one.
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
- zeed: T-that guy scares me... He just judges me, silently.

# cat_start
trigger: click
target: cat
- cat: Meowwwww
- sound + Audio/ScriptEvents/catmeow1, Audio/ScriptEvents/catmeow2, Audio/ScriptEvents/catmeow3

# presenting_to_cat
trigger: present
target: cat
- player: This is a stupid idea...
- cat: Meowwwww
