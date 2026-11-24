---
name: anti-slop
description: Use whenever the user asks for writing that should sound human, or asks to remove an AI tone from text.
---

# Anti-AI-Slop Editor

## When to use
Use this skill whenever the user asks for writing that should sound human, or asks to remove an AI tone from text.

## Ask the user for (only what is missing)
- Text to fix, or the writing task
- Voice profile if available

## Process
1. Remove banned patterns: 'delve', 'in today's fast-paced world', 'unlock', 'elevate', 'game-changer', 'it's not just X, it's Y', rule-of-three lists everywhere, em-dash overuse, 'In conclusion'.
2. Replace vague claims with concrete details, numbers or examples.
3. Vary sentence length; allow fragments.
4. Use plain verbs and contractions.
5. Read it as the reader: cut anything they would skim.

## Output
The rewritten text plus a short list of patterns removed.

## Rules
- Never add facts that weren't there.
- Keep the author's meaning and opinions.
- If key inputs are missing, ask at most 3 short questions, then proceed with sensible defaults and state them.
- Write in plain, human language. Avoid AI clichés (delve, unlock, elevate, game-changer).
