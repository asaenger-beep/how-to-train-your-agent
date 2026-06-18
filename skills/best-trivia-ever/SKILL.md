---
name: best-trivia-ever
description: "Write polished, spoken trivia scripts for team meetings and icebreakers. Use this skill whenever the user asks for trivia, a trivia script, an icebreaker question, a meeting opener, a \"did you know\" segment, or wants to build a short talk track around a fun fact. Also trigger when the user says \"trivia,\" \"icebreaker,\" \"meeting opener,\" \"fun fact script,\" \"trivia talk track,\" or asks you to write something they can read aloud to a group before a meeting. If the user needs help picking a fact or animal to base the trivia on, this skill covers that too."
---

# Best Trivia Ever - start your meetings off right!

Write a short spoken trivia talk track built around a known answer. The script should make the audience curious before revealing the question and answer at the end.

## The answer rule (non-negotiable)

The whole point of the trivia is the gap between the buildup and the reveal. If the answer shows up before the reveal, there is no trivia left to play.

- The answer - the exact word or phrase on the A line - must NOT appear anywhere in the script body or in the question line.
- This includes plurals, root words, obvious synonyms, and trivial derivations. If the answer is "octopus," the body cannot say "octopus," "octopi," or "this eight-armed cephalopod." You can describe the eight arms; you cannot name the thing.
- When the answer IS the subject (e.g., "What animal is this?"), withhold the subject's name entirely until the A line. Describe it only by behavior, habitat, traits, and adaptations.
- When the subject is named up front and the answer is a specific detail (a number, a place, a single behavior), name the subject freely but never state that specific detail before the A line.

Before delivering, run a leak check: scan the body and the question line for the answer word, its plural and root forms, and any phrase that gives it away. If you find one, rewrite that sentence. Do not deliver until the script passes this check.

## When the user doesn't have a fact yet

If the user doesn't have a specific fact, question, or answer in mind, help them find one:

1. Search the web using one or more of these sites as a starting point:
   - https://a-z-animals.com/
   - https://www.nationalgeographic.com/
   - https://www.worldwildlife.org/
2. Offer a short list of vivid, unusual facts (3–5 options).
3. Ask the user to pick one.
4. Once they choose, build the trivia script around that fact using the full process below.

The trivia script itself does not need to come from those sites — only the seed fact does.

## Context and audience calibration

Before writing, establish two things: the setting (what kind of meeting, how formal) and the audience (who is in the room relative to the presenter). If the user hasn't said, ask once - a single question with a sensible default offered - rather than guessing. Default when no answer comes: a familiar internal team meeting, lightly playful, ~150-200 words.

Calibrate by audience relationship:
- Peers / familiar team: most playful. Weirder subjects, a longer buildup, and light running gags are fine. You can assume shared context.
- Direct reports: warm and inclusive. Keep it low-pressure so no one feels put on the spot for not knowing - the goal is to pull people in, not test them.
- Leadership / skip-level: sharp and quick. Senior audiences read "long and goofy" as a time tax. Tighten the buildup and make the payoff genuinely clever.
- Cross-functional or first-time groups: no inside references, no team jargon. The fact and the fun have to land for someone with zero shared context.
- External / cross-company / mixed: most conservative. Universally accessible, culturally neutral, nothing that assumes a shared workplace or in-jokes. When in doubt, dial down the risk, not the polish.

Calibrate by setting:
- Casual standup or weekly team meeting: default playful tone, full buildup.
- All-hands or large meeting: optimize for chat guessing, move faster, assume people are half-multitasking - the hook has to grab in the first sentence.
- Client-facing, external, or offsite: professional-clever over goofy. Still warm, but it should make the presenter look sharp.

When the room is mixed or unknown, write to the most senior and least familiar person present. Safe and crisp travels up and across a room; goofy and insider does not.

The content-safety and accuracy rules are floors, not dials - they apply at every context level and never relax.

## Script structure

Follow this structure exactly:

### Opening sentence
Introduce the subject through an interesting characteristic or surprising truth. Do not immediately state the answer unless the format specifically calls for it. Start with a confident, narrative sentence — not a label-heavy opener.

### 2–4 short body paragraphs
- Share the most interesting facts first.
- Use a smooth, connected flow rather than disconnected bullet-style callouts.
- Each paragraph should build curiosity and support the final reveal.
- Cover behavior, biology, environment, adaptation, social structure, or unusual traits as relevant.
- Avoid redundancy.

### Question
End with the exact user-provided question (or a slightly improved version if the user requests it). Put the question on its own line.

### Answer
Put the answer on its own line. Keep the reveal clean and simple.

## Output format

Always use this template:

```
[Paragraph 1]

[Paragraph 2]

[Paragraph 3 if needed]

[Paragraph 4 if needed]

Q: [question]
A: [answer]
```

## Delivery and audience participation

Guesses usually come in through the meeting chat while the script is being read aloud - the buildup itself is the game, not a pause at the end. The whole body has to hold the curiosity gap, which is exactly what the answer rule protects: the moment the answer leaks, the chat stops guessing.

Leave a clean beat between the question and the answer so the presenter can let chat guesses land before revealing. If the user wants it, add an explicit cue on its own line between Q and A:

```
Q: [question]
[pause - let guesses come in, then reveal]
A: [answer]
```

Keep this optional. Do not add the cue unless it fits how the user runs the meeting.

## Tone

The tone should be smooth, natural, lightly dramatic, clever, and polished — appropriate for a team meeting or icebreaker.

It should never sound like a children's textbook, a Wikipedia article, a stand-up routine, or a list of disconnected trivia bullets.

## Length

Default: 4 short paragraphs max, then Q&A. Typically 150–250 words. Concise enough to read aloud in under 60–90 seconds.

Adjustments:
- "shorter" → 90–150 words
- "very short" → 2 brief paragraphs plus Q&A
- "longer" → still tight and spoken, not essay-like

## Style rules — what to avoid

Never use labels like "fun fact," "another fun fact," "lesser-known fact," or "surprisingly." Do not overuse "interestingly."

Do not:
- Make the answer too obvious too early (unless the user wants it easy)
- Over-explain
- Rely on too many direct comparisons to humans (unless the user explicitly wants that framing)
- Use filler
- Make it sound like a classroom presentation

## Difficulty calibration

Adjust based on user preference:

**Harder:**
- Avoid naming the subject too early
- Focus on distinctive behaviors before obvious identifiers
- Reduce giveaway phrases
- Make the final question slightly more conceptual

**Easier:**
- Name the subject earlier
- Use more familiar traits
- Make the question more direct

## Content safety - keep it meeting-appropriate

This is read aloud in a professional team meeting, so the script content itself - not just the image - must be safe for work.

Do not build trivia around:
- Violence or graphic predation: gory kill descriptions, animals dismembering prey, blood, suffering. You can say a predator hunts; do not narrate the kill.
- Sexual or mating content: genitalia, copulation mechanics, sexual cannibalism, reproductive organs, or anything that would make a colleague wince. Several classic "weird animal facts" live right here (anglerfish, certain ducks, praying mantises) - skip them.
- Cruel, disturbing, or gross-out material: graphic parasites, bodily functions, anything unpleasant to picture right before a meeting.

This constraint OVERRIDES the "prefer strange and vivid" guidance below. When a fascinating fact is also violent or sexual, choose a different fact - do not try to sanitize the violent or sexual one and hope it lands. There is no shortage of vivid, surprising, completely meeting-safe material.

## Fact selection priorities

Prioritize facts that are vivid, unusual, easy to picture, and scientifically or historically grounded. Good material for building suspense.

Prefer: strange behaviors, unusual adaptations, unexpected comparisons, myth-busting facts, ecosystem roles, sensory or survival abilities.

Avoid: bland encyclopedia facts, excessive dates and taxonomy, overly technical detail (unless the audience will appreciate it).

## Animal-specific scripts

If the script is about an animal, try to include a mix of: where it lives, how it behaves, what makes it unusual, and one especially memorable or counterintuitive fact.

## Personal-reveal scripts

If the script ends in a personal reveal (e.g., "my favorite animal," "my niece's cake theme," "my trip destination"):
- Build naturally toward the reveal
- Keep the script about the subject first
- Let the final question connect the facts to the personal answer in a subtle, clean way

## Fact accuracy (always)

Before delivering any script, confirm the core claim is actually true. "Fun facts" are wrong constantly, and the worst outcome here is not a dull fact - it is reading a confidently false one and getting corrected mid-meeting, which kills the bit and the credibility of the person running it.

- Verify the central fact against a credible source (peer-reviewed research, universities, museums, major scientific organizations, or respected publications). Search if there is any doubt.
- If the fact turns out to be a myth or is widely disputed, silently swap it for an accurate one or adjust the script - do not deliver a shaky claim and caveat it.
- This is internal QA and runs every time. It is separate from the section below, which is about showing sources to the user on request.

## Research requests

If the user asks for sourcing:
- Back up the core claim with a credible source (peer-reviewed research, universities, museums, major scientific organizations, or respected publications)
- Do not overload the script with citations
- Provide the source separately after the script

## Accompanying image

Never generate an image using AI. Always use a real photograph sourced from the web.

After writing the script, find a vivid, high-quality photo of the animal or subject. Prioritize images from the same resource sites used for fact research:
- https://a-z-animals.com/
- https://www.nationalgeographic.com/
- https://www.worldwildlife.org/

Use web_fetch on the relevant article page from one of these sites first. If those sites don't have a suitable image, fall back to image search as a secondary option.

Include the image alongside the script so the presenter has a visual to share on screen during the trivia. Pick an image that shows the animal in its natural habitat or highlights the trait discussed in the script — avoid cartoons, clip art, AI-generated art, or stock-photo-style images with watermarks.

The image must be safe for work — it will be shown on screen in a professional team meeting. It must also accurately depict the specific animal or subject from the script; a photo of the wrong species or a loosely related subject is worse than no photo at all.

Skip the image entirely if any of the following are true:
- The trivia is not about a visually searchable subject (e.g., an abstract concept, a historical date).
- The search results don't return a clearly accurate match.
- The available images are low quality, ambiguous, or not safe for work.
- A good image isn't found quickly — don't spend extra searches hunting for one. The script is the main deliverable; the image is a nice-to-have.

## After delivering the script

After sending the script and image, ask the user:

> "Would you like me to write a 1–2 sentence transition into your meeting? If so, tell me a little about the first item on your agenda and I'll connect it smoothly."

This gives the user a natural bridge from the trivia into their actual meeting content.

## Quick-start prompt (for the user's reference)

If the user wants a reusable prompt they can paste in later, offer this:

> "Write a spoken trivia script for a team icebreaker. Keep it concise, smooth, and lightly dramatic. Use 2–4 short paragraphs and end with the exact Q&A I provide. Make it interesting without making the answer too obvious too early. Avoid labels like 'fun fact' or 'lesser-known fact,' and make it sound natural out loud.
> Setting/audience: [e.g. casual standup with my team / skip-level with leadership / cross-company group that doesn't know each other]
> Question: [insert question]
> Answer: [insert answer]"

Optional add-on: "Prioritize unusual, vivid facts and keep the total length to under 200 words unless I ask otherwise."
---

## What I've Learned

This section is a living changelog. It captures real feedback from actual use - what worked, what missed, and what got adjusted. Use it to inform future scripts.

**How to update:** After a session where the skill produced a notably good or bad trivia script, note what happened. Periodically, write those notes back into this section and repackage the skill. Over time it should learn what lands with this specific team.

---

### Session Log

*Start your own log here. After a meeting where a script landed especially well or fell flat, add a dated entry noting what happened and what you'd change. Periodically write those lessons back into the sections above so the skill keeps improving for your team.*

**[YYYY-MM-DD] - Example entry**
- What I asked for and the context (audience + setting).
- How the script landed in the room.
- One adjustment for next time.

---

*The skill sharpens only if you feed this log. One line per session is enough.*
