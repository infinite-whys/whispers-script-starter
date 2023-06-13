---
script: GIRAFFE
target: hint
---

# hints
trigger: hint
- player: Hello
----
label: task_1
- player: I shall visit the traveling circus, where can they be?
- [#](#use_hint)
---
label: hint_1
label: task_1
- player: The big tent at the main square must belong to the traveling circus.
- player: I shall find out more about the circus by talking to one of their people.
---
label: task_2
- player: The fortune teller said Mrs Johnson has a secret or two. What is the secret from Mrs Johnson’s past?
- [#](#use_hint)
---
label: hint_2
label: task_2
- player: To find out the secret from Mrs Johnson’s past. 
- player: I shall speak to someone who knew Mrs Johnson a long time ago. 
- player: But since it's a secret, Mrs Johnson may attempt to cover it.
- player: The conversation may go a little back and forth. 
---
label: task_3
- player: Mrs Johnson was shot at the main square last night. It's my job to investigate this unfortunate incident. 
- [#](#use_hint)
---
label: hint_3
label: task_3
- player: Mrs Johnson was shot at the main square. Did she leave anything at the scene?
- player: Were there any eyewitnesses?
---
label: task_4
- player: A note was found in the victim's purse. Who wrote this note?
- [#](#use_hint)
---
label: hint_4
label: task_4
- player: Whoever wrote the note may not admit they have written it. So, the handwriting of the note holds the key to solving the case.
- player: The banker must have many signatures from their customers, perhaps he could offer some help?
---
label: task_5
- player: Who murdered Mrs Johnson?
- [#](#use_hint)
---
label: hint_5
label: task_5
- player: To answer the question, I shall first find out what the murder weapon was, and who had access to it.
- player: Did the murderer shoot Mrs Johnson on purpose? If so, why? 
- player: If it was a mistake, who could the shooter have mistaken her for?


# use_hint
- player: Should I use a hint?
- [Yes](#yes_hint)

# yes_hint
- player: Alright...
- hint + 
- [#](#hints)
