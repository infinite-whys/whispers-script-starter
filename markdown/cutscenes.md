---
script: S01
---
# CINEMATIC_INTRO
target: bartender
trigger: intro
location: saloon
target: bartender
- zeed: Did you hear what happened in the mine last night?
- bartender: No, what was it?
- zeed: There was this almighty crash... and a scream...
- bartender: Ha! Would anyone be surprised by the noises at the mine? That place is haunted!
- zeed: ...
---
# CINEMATIC_Q1RIGHT
target: priest
trigger: Q1RIGHT
location: church
target: priest
- priest: My poor girl, if the foreman had not lured her into the mine that night, she would still be with us.
---
# CINEMATIC_Q1WRONG
target: miner
trigger: Q1WRONG
location: mine
target: miner
- miner: The victim in the mine?
- miner: I don't know who it was, but one thing I'm sure of is it was a little girl.
---
# CINEMATIC_Q2RIGHT
target: mayor
trigger: Q2RIGHT
location: townhall
target: mayor
- mayor: Are you saying this knife is the murder weapon?
- mayor: I'll take your word for that.
---
# CINEMATIC_Q2WRONG
target: mayor
trigger: Q2WRONG
location: townhall
target: mayor
- mayor: This? The murder weapon?
- mayor: I'm not so convinced but I will hear you out.
---
# CINEMATIC_Q3RIGHT
target: priest
trigger: Q3RIGHT
location: office
target: priest
- priest: ...because of him, my poor girl is with God now.
- priest: I do not regret what I have done.
---
# CINEMATIC_Q3WRONG
target: mayor
trigger: Q3WRONG
location: townhall
target: mayor
- mayor: I'm afraid there's not enough evidence to support your theory, my friend.
- mayor: They could not possibly be the murderer.
---
# CINEMATIC_WhatHappened1
target: ui_item
trigger: WhatHappened1
location: UI
target: ui_item
- ui_item: It all started with the body, battered and bloodied beyond recognition by a cave-in. 
---
# CINEMATIC_WhatHappened2
target: ui_item
trigger: WhatHappened2
location: UI
target: ui_item
- ui_item: The only clue to the body’s identity was a pendant with a portrait.
---
# CINEMATIC_WhatHappened3
target: bartender
trigger: WhatHappened3
location: saloon
target: bartender
- bartender: The woman in that pendant, that’s my dear Francesca, my ex-wife from 7 years ago. She walked out on me and went missing.
---
# CINEMATIC_WhatHappened4
target: ui_item
trigger: WhatHappened4
location: UI
target: ui_item
- ui_item: The foreman was murdered the very next night. What could the connection be?
---
# CINEMATIC_WhatHappened5
target: miner
trigger: WhatHappened5
location: mine
target: miner
- miner: With the foreman gone, there’s no need to keep quiet.
- miner: The victim in the mine can’t have been Francesca. It was a young girl.
---
# CINEMATIC_WhatHappened6
target: banker
trigger: WhatHappened6
location: bank
target: banker
- banker: The foreman was involved in a controversial purchase. He wanted to dig under the church’s graveyard.
- banker: So he was buying the Church unless the priest could offer more.
---
# CINEMATIC_WhatHappened7
target: ui_item
trigger: WhatHappened7
location: UI
target: ui_item
- ui_item: The child’s diary told all.
---
# CINEMATIC_WhatHappened8
target: priest
trigger: WhatHappened8
location: church
target: priest
- priest: She was my adopted daughter, and Francesca was her mother.
- priest: She’d overheard that her mother’s grave was in danger. She knew that there were valuable gems in those mines.
- priest: She wanted to protect the Church. She was a brave girl. She took matters into her own hands, and tragedy ensued.
- priest: The foreman’s schemes took everything from me. With my girl dead, I did what any parent would do.
---
# CINEMATIC_WhatHappened9
target: ui_item
trigger: WhatHappened9
location: UI
target: ui_item
- ui_item: The priest took revenge.
---
# CINEMATIC_WhatHappened10
target: butcher
trigger: WhatHappened10
location: butchers
target: butcher
- butcher: So it was Francesca’s child in the mine? And Francesca in the graveyard? And the young girl’s father? Don’t tell me…
