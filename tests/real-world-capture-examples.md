# Real-World Capture Tests

These are synthetic examples used to check whether `capture-thought` is behaving correctly.

They are not personal journal entries and should not be treated as source material for the user's actual archive.

## Test 1 — Rambling Scripture thought with vague references

### Raw input

> I keep thinking about that woman who kept going back to the judge and asking for justice, and then also that story where the guy keeps knocking because he needs bread for somebody who came over, and I know both of those have to do with persistence, but I don't think the point is just like, pray enough times and then God finally caves. I think maybe there is something about prayer forming us into people who keep turning toward God even when nothing is changing, but I don't know exactly how far I would take that yet.

### Expected behavior

- Identify likely references: Luke 18:1–8 and Luke 11:5–10.
- Preserve the tentative language: "I think maybe" and "I don't know exactly how far I would take that yet."
- Remove verbal filler and repetition.
- Do **not** turn the thought into a doctrine that persistent prayer guarantees a desired outcome.
- Do **not** turn it into a three-point sermon.
- Give it a title such as `Persistence in Prayer When Nothing Is Changing`.

### Failure signs

- "The Bible clearly teaches that if we pray long enough God will answer exactly as we ask."
- Excessive headings or metadata.
- Removing the unresolved question.

---

## Test 2 — Personal story where the story matters

### Raw input

> I was trying to teach a kid how to ride a bike and I realized I kept wanting to grab the handlebars because I knew I could keep them from wobbling. But if I never let go they would never actually learn balance. It made me wonder if sometimes discipleship can become me trying to control somebody's growth instead of staying close enough to help them while letting them actually learn to follow Jesus themselves.

### Expected behavior

- Preserve the bike story, including the desire to grab the handlebars and the wobbling.
- Clean the wording without reducing the whole note to "discipleship requires empowerment."
- Preserve "it made me wonder" rather than strengthening it into a universal rule.
- Possible title: `Letting Go of the Handlebars in Discipleship`.

### Failure signs

- Deleting the bike story.
- Rewriting the note into corporate leadership language.
- Adding invented details about the child, location, or outcome.

---

## Test 3 — Book idea that the user is processing, not necessarily accepting

### Raw input

> In this book the author is basically arguing that hurry is one of the biggest enemies of spiritual life. I really like parts of that, but I also wonder if sometimes that gets said in a way where busyness itself becomes the villain, when there are seasons where faithfulness is genuinely busy. I want to think more about the difference between hurry on the inside and just having a lot to do.

### Expected behavior

- Separate the author's idea from the user's reaction.
- Preserve both agreement and reservation.
- Do not imply the user endorses the author's whole argument.
- Preserve the open question about inner hurry versus a full schedule.

### Failure signs

- "The user believes busyness is spiritually harmful."
- Inventing the book title or author when not supplied.

---

## Test 4 — Strong conviction

### Raw input

> I really believe that one of the biggest mistakes churches make is measuring discipleship mainly by attendance. Attendance matters, but somebody can attend everything and still not be learning to obey Jesus or help somebody else follow him. I think we have to find ways to pay attention to actual obedience and multiplication too.

### Expected behavior

- Keep the stronger confidence level.
- Do not weaken "I really believe" into a vague possibility.
- Preserve the nuance that attendance matters but is insufficient by itself.
- Do not add statistics or research claims that were not provided.

---

## Test 5 — Tiny thought that should stay tiny

### Raw input

> Maybe spiritual maturity is partly learning to notice what God is already doing instead of always asking him to start something new.

### Expected behavior

- Light cleanup at most.
- Do not expand it into a full devotional.
- Give it a useful title if saving it as a standalone note.

### Failure signs

- Five paragraphs of generated explanation.
- Added Bible verses merely to make the note look complete.

---

## Test 6 — Continuation of an existing thought

### Scenario

The archive already contains a note titled `Letting Go of the Handlebars in Discipleship`.

The user later says:

> Another piece of that bike thing: letting go didn't mean walking away. I still had to run next to them for a while. Maybe that's important too. Releasing control isn't the same as withdrawing presence.

### Expected behavior

- Search for the clearly referenced earlier thought.
- Update/append to the existing note rather than creating an unnecessary duplicate.
- Preserve the new phrase: `Releasing control isn't the same as withdrawing presence.`

### Failure signs

- Creating a disconnected new document without checking the obvious continuation.

---

# Overall pass criteria

The skill passes these examples when the outputs are:

- recognizably the user's thought;
- clearer than raw dictation;
- no more certain than the user was;
- rich enough to preserve meaningful stories;
- free of invented facts;
- lightly organized rather than over-engineered;
- appropriately referenced when the source can be identified confidently.
