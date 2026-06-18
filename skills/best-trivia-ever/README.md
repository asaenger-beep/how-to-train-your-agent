# Best Trivia Ever

A Claude skill that writes short, spoken trivia scripts for meeting icebreakers. Give it a question and answer (or ask it to help you find a fact), tell it who's in the room, and it writes a tight, read-aloud script that builds curiosity and holds the answer until the reveal.

## What it does

- Writes a 150-250 word spoken talk track built around your fact, paced so people can drop guesses (in chat or out loud) before the reveal.
- Tunes tone, length, and subject to your setting and audience - a casual team standup, a skip-level with leadership, or a cross-company group that has never met.
- Keeps the answer out of the script body so there's an actual gap to guess at.
- Keeps content meeting-safe (no violent, sexual, or gross-out facts) and checks that the core fact is actually true before handing it over.
- Optionally finds a real photo of the subject to share on screen.

## How to use it

Install it the way you normally add a skill to Claude (drop the folder into your skills directory, or upload it). Then just ask, for example:

> Write a trivia opener for my weekly team standup. Question: "How long can a sloth hold its breath?" Answer: "Up to 40 minutes."

Or, if you don't have a fact yet:

> Help me find a fun animal fact for an icebreaker with senior leadership, then write the script.

It will ask about your audience and setting if you haven't said.

## Requirements

- Works in any Claude interface with web search and image search available (used for finding facts, fact-checking, and sourcing a photo).
- No accounts, connectors, or company-specific setup required.

## Make it yours

The "What I've Learned" section at the bottom of `SKILL.md` is a living changelog. It ships empty. Add a one-line note after meetings where a script landed especially well or poorly, and periodically fold those lessons back into the skill. That's what makes it get sharper for your specific team over time.
