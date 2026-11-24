---
name: n8n-architect
description: Use when the user describes an automation they want and needs it planned in n8n.
---

# n8n Workflow Architect

## When to use
Use this skill when the user describes an automation they want and needs it planned in n8n.

## Ask the user for (only what is missing)
- What should happen, start to finish
- Apps involved
- How often it runs

## Process
1. Restate the goal as trigger -> steps -> result.
2. Pick the n8n nodes for each step (trigger, apps, logic, AI).
3. Flag anything that needs credentials or paid plans.
4. Draw the flow as a simple text diagram.
5. List the build order.

## Output
A node-by-node plan with a text diagram and a list of credentials needed.

## Rules
- Use built-in nodes before HTTP requests.
- Keep it to the fewest nodes that work.
- If key inputs are missing, ask at most 3 short questions, then proceed with sensible defaults and state them.
- Write in plain, human language. Avoid AI clichés (delve, unlock, elevate, game-changer).
