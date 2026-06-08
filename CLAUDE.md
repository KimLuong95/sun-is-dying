# Project Guide — *Sun Is Dying*

Orientation for any AI (or person) picking up this project. This is a **novel-design repo**, not
code.

## What this is
A deep-future sci-fi series. ~5 billion years from now, the Sun dies; humanity has split into
five branches that disagree about what a human even is; one family (House Vael) keeps the dying
Earth and is torn apart along the same lines. Full concept: [`STORY-SPINE.md`](STORY-SPINE.md).

## Where everything lives
- `STORY-SPINE.md` — premise, locked decisions, decision log. **Single source of truth.**
- `world/` — setting, Earth, how humanity is organized.
- `factions/` — the five branches (Originists, Ascended, Digitals, the Choir, the Made).
- `religions/` — four belief systems built on the "was the universe made?" mystery.
- `characters/` — House Vael cast; each character has its own folder with `bio.md` and a
  `growth/` folder for dated change-files. See `characters/_growth-template.md`.
- `style/` — **how the book is written.** Read before drafting any prose.
- `story/` — per-book outlines *(not written yet — next step).*

## Working rules (these matter to the author)
1. **Plain, easy language.** This is read on a phone. No jargon walls. Explain the strange
   through what it does to a person, never with a manual. (`style/04-worldbuilding-on-the-page.md`)
2. **Do not sound like AI.** The author cares about this above almost everything. Every prose
   pass runs the anti-AI-tells kit (`style/01-avoiding-ai-tells.md`) and the 6-pass revision
   checklist (`style/05-the-revision-pass.md`).
3. **No branch is the villain.** Each is right from inside. If one becomes the bad guys, it's broken.
4. **Push to GitHub after each meaningful chunk** so the author can read on mobile and spar with
   other AIs. Commit messages plain and descriptive.
5. **Repo visibility:** this repo is **public on purpose** (so the author can share/spar). This
   is the one exception — every *other* repo stays private per the author's global rule.

## Current status
Worldbuilding complete (world, factions, religions, characters, style). Next: the story outline
in `story/`, then drafting Chapter 1.
