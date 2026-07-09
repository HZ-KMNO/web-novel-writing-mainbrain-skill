# Modern Chinese Speech Calibration

Use this reference when Chinese fiction drafts sound unlike real Chinese speech, when de-AI polishing creates broken short sentences, or when an agent needs a stronger standard for dialogue, narration, and everyday reasoning.

Source basis: read-only rereading and statistical inspection of the local EPUB case files for 王小波作品大全集、刘震云全集作品集典藏版、三体、活着. This file extracts transferable mechanisms only. Do not copy or imitate original sentences, plots, character shells, or signature author voices.

## Core Standard

```text
Say what a person in this scene would actually say,
with the amount of context, hesitation, face-saving, self-protection,
and everyday wording that the scene requires.
```

Modern Chinese "human speech" is not created by cutting sentences shorter. It is created by preserving:

- who is speaking or narrating
- what they are trying to protect
- what they know and do not know
- what concrete thing is in front of them
- what ordinary explanation they would try first
- what extra half-sentence a real person would add so others understand

## Four Calibrators

### 1. 余华 / 活着: plain oral narration with event pressure

Learn:

- Simple narration can be powerful when it follows lived sequence: this happened, then that happened, then the consequence landed.
- Emotion is carried by events, actions, objects, and later consequences, not by repeated emotional labels.
- A sentence can be plain without being empty. The reader should always know who did what to whom and why it matters.
- First-person or oral narration can keep "I saw", "I thought", "later", "at that time" style orientation when it helps the listener follow.

Use in web-novel writing:

- When a scene is emotionally heavy, do not rush to literary abstraction. Put a person, an object, and a consequence in the same frame.
- For grief, fear, shame, or regret, first write what the person did with their hands, where they stood, what object they avoided, and what ordinary sentence they could not say.
- Keep the sentence readable. Plain does not mean clipped.

Do not imitate:

- Do not turn every chapter into rural oral memoir tone.
- Do not copy cadence or famous simplicity as a surface style.

### 2. 刘震云: social speech, errands, face, and oral self-defense

Learn:

- People often speak to avoid responsibility, save face, test others, pass messages, dodge blame, or keep a relationship usable.
- Colloquial language is not random chatter. It is social action.
- Repetition, "not X but Y" movement, small corrections, and practical wording make speech feel like people negotiating reality.
- Everyday absurdity comes from procedures, errands, announcements, favors, documents, relatives, officials, neighbors, and messages colliding.

Use in web-novel writing:

- Before writing dialogue, ask: what is this person trying not to admit?
- Let characters say things slightly indirectly when they are afraid of blame, embarrassment, authority, or relationship damage.
- In school, hospital, police, company, village, and family scenes, let institutional language become human language when characters repeat it.
- For example, do not make a student say a policy line like a form. Let them say what the policy means for their room, class, score, family, or money.

Do not imitate:

- Do not make dialogue noisy without purpose.
- Do not force every character into the same comic or argumentative cadence.

### 3. 王小波: narrator judgment and thinking while speaking

Learn:

- A narrator can sound alive because they judge, doubt, defend themselves, and think through a premise.
- Irony works when it has a logical target. It is not just a strange metaphor or clever sentence.
- A speaking mind may move through "I thought this was reasonable -> then I noticed the contradiction -> so I changed my judgment."
- Humor and rebellion come from the narrator's angle on the world, not from word tricks alone.

Use in web-novel writing:

- Give the viewpoint character a real judgment, not just camera movement.
- When the protagonist notices something wrong, let them make a first explanation, reject it, then choose a more uncomfortable explanation.
- In suspense and ghost stories, narrator judgment can create dread: the person tries to be reasonable, but reason keeps making the scene worse.

Do not imitate:

- Do not copy 王小波's strong personal voice as default web-novel prose.
- Do not let cleverness replace scene clarity.

### 4. 刘慈欣 / 三体: large ideas anchored in human pressure and institutions

Learn:

- Big concepts become readable when tied to concrete institutions, meetings, equipment, documents, historical pressure, professional roles, or visible consequences.
- Exposition can work when the speaker has a reason to explain and the listener has a reason to care.
- Technical or cosmic ideas still need human stakes: fear, responsibility, secrecy, betrayal, awe, institutional pressure, survival.
- Characters should not explain a setting because the author needs it. They explain, hide, argue, or simplify because of their role and situation.

Use in web-novel writing:

- If a ghost rule, system rule, or worldbuilding idea appears, attach it to a witness, object, procedure, failure, death, report, or urgent choice.
- When writing rules, ask: who discovered it, who benefits from hiding it, who misunderstands it, and what happens if it is wrong?
- Use professional speech only for characters who would naturally speak that way, and still translate consequences into ordinary stakes.

Do not imitate:

- Do not turn chapters into lectures.
- Do not make ordinary students, relatives, victims, or passersby speak like scientists or official reports.

## Practical C-Draft Gate

Before finalizing Draft C, scan every suspect sentence through these questions:

1. Would a Chinese reader immediately know who is doing what?
2. Would this person say it this way in this room, under this pressure?
3. Is a useful oral support word missing, such as "了", "也", "还", "就", "得", "要", "别", "吧", "呢", "不是", or "就是"?
4. Did de-AI polishing delete subject, context, or social motive?
5. Is the line a field label pretending to be prose?
6. Is the line a translated structure wearing Chinese words?
7. Is the line trying to be literary but making the event harder to understand?
8. Does the emotion come from the event, or only from adjectives?

If any answer fails, rewrite before continuing.

## Common Failure Types

### Field Sentence

Bad pattern:

```text
Object. Status. Conclusion.
```

Why it fails:

It sounds like a form, a game UI, or a broken subtitle, not narration.

Repair:

```text
Person notices object -> object behaves oddly -> person gives an ordinary explanation -> the explanation fails.
```

### Over-Compressed Dialogue

Bad pattern:

```text
No subject, no social motive, no natural filler, only bare conclusion.
```

Repair:

Add the real spoken bridge:

```text
what happened -> what I think it means -> what I want you to do / not do
```

### Fake Literary Terror

Bad pattern:

```text
abstract fear + vague metaphor + no physical evidence
```

Repair:

Use a visible, audible, touchable abnormality:

```text
light, lock, smell, footprint, voice, phone, file, photo, hand movement, silence after a question
```

### Official Language in a Human Mouth

Bad pattern:

```text
ordinary character repeats document wording without emotion or need
```

Repair:

Let the document stay formal, but let the character translate it into lived consequence:

```text
What does this mean for my room, my shift, my record, my family, my money, my safety, or my blame?
```

## Rewrite Method

When a sentence "does not sound human", do not polish it in place. Rebuild it:

1. Name the speaker or viewpoint.
2. Name the immediate object or situation.
3. Name what the person wants right now.
4. Name what they are afraid of admitting.
5. Write the line in ordinary order.
6. Read it aloud.
7. Restore useful Chinese particles and oral supports.
8. Cut only after the sentence is clear.

## Agent Instruction

When the user complains about "不像人话", "不像中国人说话", "AI 腔", "翻译腔", "太短", "像字段", or "看不懂":

- Stop producing new plot.
- Locate the bad sentence and its neighboring sentences.
- Classify the failure type.
- Rewrite using the four calibrators above.
- Scan the same chapter for repeated failure patterns.
- Record the language issue in the chapter's final check.

