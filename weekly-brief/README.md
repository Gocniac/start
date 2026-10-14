# Weekly Business Brief

A Claude Routine writes a brief every Sunday at about 17:55 (Europe/Helsinki) with:
1. Three business ideas
2. Lessons of the week (business, finance, technology)
3. Trends & reading
4. Challenge of the week

## Memory

The agent reads `memory.md` before writing each brief and updates it afterwards, so it:
- never repeats a business idea or lesson topic,
- builds lessons on top of what you have already learned,
- remembers your feedback and interests.

Each brief is saved in `briefs/YYYY-MM-DD.md`.

## Giving feedback

Reply in the brief's Claude session (or edit `memory.md` directly), e.g.
"more fintech ideas", "finance lesson was too basic", "I'm exploring idea #2".
The agent records it under **About me & feedback** and uses it from then on.
