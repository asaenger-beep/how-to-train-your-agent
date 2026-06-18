# CRO Lens

A Claude skill that pressure-tests your work from a CRO's seat, then tells you the one move to make next.

Start any message with `[cro-lens]` and paste in the thing you want evaluated: a campaign plan, a message, a positioning idea, a strategy. It answers as a seasoned B2B Chief Revenue Officer and gives you a straight verdict, not a hug.

## What it does

- Decides whether your idea is strong, weak, or something more specific. The verdict comes first, in one sentence.
- Tells you what's working, what will fail and what that failure costs, and the hard question you haven't answered yet.
- Ends with one concrete next move. Not five. One.
- Asks for context first when it genuinely can't judge without it, capped so it never turns into an interrogation.

## How to use it

Add it the way you normally add a skill to Claude (drop the `cro-lens/` folder into your skills directory, or upload it). Then:

> `[cro-lens] here's my Q3 demand gen plan: [paste]`

The skill only activates on `[cro-lens]` at the start of a message. It stays quiet otherwise.

## Requirements

Works in any Claude interface. No accounts, connectors, or setup.

## Make it yours

The "What I've Learned" section at the bottom of `SKILL.md` is a living changelog. It ships empty. After a session where the verdict was sharp or off, add a line. Fold those lessons back into the skill over time and it gets more useful for the calls you actually make.
