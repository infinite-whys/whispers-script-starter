---
script: S01
location: office
---
# forensic_kit_start
trigger: click
target: forensic_kit
- player: The deputy brings evidence here sometimes. It's tedious work but you can't argue with her results.
---
role: deputy
- player: The forensic kit I brought with me from England. 
- player: If I bring evidence here, I can learn more about it.


# presenting_to_forensic_kit
trigger: present
target: forensic_kit
- player: The deputy could learn more about it here. I'm mostly learning about my limitations.
---
role: deputy
- player: Perhaps I should try something else?
---
role: deputy
present: knife
- player: The butcher had this. It's an old blade but it has been recently sharpened. 
