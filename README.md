# grok-bots

Private git home for **all** of Ferdinand's Grok Bot recipes. Each agent lives under `agents/<slug>/` so this repo scales past a single bot.

## Layout

```
agents/
  ai-researcher/     # technical deep-dives + X Following digests
    BOT.md           # portable recipe (profile, memories, skills, routines)
    README.md
  # add more: chief-of-staff/, jordan-belfort/, …
```

## Agents

| Slug | Role |
|------|------|
| [`ai-researcher`](agents/ai-researcher/) | Architectures / APIs / systems deep-dives + weekday X Following digests |

## What does *not* live here

- **X digests ledger:** [feraranas/x-following-digests](https://github.com/feraranas/x-following-digests) (public) — `digests/`, `index.jsonl`, `TAGS.md`, `tools/search.py`. Keep that repo separate; link from agent READMEs.

## Adding an agent

1. Create `agents/<kebab-slug>/`.
2. Add `BOT.md` (profile, durable conventions, skills, routine job text — scrub secrets).
3. Add a short `README.md` with pair-with links (templates, related repos).
4. Link the row in this root README table.

Prefer the published Grok Bot template for one-click recreate; use this repo for offline/git history across every bot.
