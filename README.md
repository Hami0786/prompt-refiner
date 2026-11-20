# Prompt Refiner

**Use it here:** https://hami0786.github.io/prompt-refiner/

Write your request the way you normally would. Prompt Refiner works out what you are actually asking and compiles a precise, structured prompt for Claude or any other AI model.

- Removes swearing, venting, slang and filler
- Splits the message into separate objectives
- Detects the platform, stack and concerns (memory, hangs, crashes, sorting, large lists, concurrency, networking, database, accessibility, test automation, security)
- Adds senior-engineer deliverables and clues, a default for every unknown, and only the rules your request triggers
- Shows a live score, the issues it found and the missing details as you type

It runs entirely in your browser (Python via Pyodide). Nothing you type is sent to a server.

## Files

- `index.html`: the web UI
- `engine.json`: the Prompt Refiner 5 Python engine, loaded into Pyodide at startup
