# content-skills

> A plug-and-play content engine for any LLM. Fork it. Extend it. Build with it.

A public skills repository of **creator brains** and **platform-optimized content frameworks** that you can pull into any LLM to generate content that actually performs — algorithmically and culturally.

---

## What This Is

`content-skills` gives any LLM a structured knowledge base of:

- **Creator Brains** — Platform-specific strategies from 20 of the world's top content creators. Each creator has a `SKILL.md` that tells any LLM how to think, structure, and distribute content the way that creator does.
- **Format Libraries** — Battle-tested content formats aligned with real platform algorithms (starting with X/Twitter).
- **Algorithm Alignment** — Format and distribution logic referenced from [xai-org/x-algorithm](https://github.com/xai-org/x-algorithm).

---

## How To Use

### With any LLM (Claude, GPT, Gemini, etc.)

1. Clone or fork this repo
2. Copy the contents of any `SKILL.md` into your LLM system prompt
3. Prompt the LLM to generate content using that creator's strategy

```bash
git clone https://github.com/YOUR_USERNAME/content-skills.git
```

**Example system prompt:**
```
You are a content strategist. Read the following SKILL.md and use it to help me create content for my brand.

[paste SKILL.md content here]
```

### Stack Multiple Skills

Combine a creator brain with a format library for maximum output quality:

```
System prompt = creators/mrbeast/SKILL.md + formats/twitter-viral-formats.md
```

---

## Repo Structure

```
content-skills/
├── README.md
├── formats/
│   └── twitter-viral-formats.md       ← X/Twitter algorithm-aligned formats
└── creators/
    ├── mrbeast/SKILL.md
    ├── mark-rober/SKILL.md
    ├── steven-bartlett/SKILL.md
    ├── dhar-mann/SKILL.md
    ├── jake-paul/SKILL.md
    ├── matt-rife/SKILL.md
    ├── rhett-and-link/SKILL.md
    ├── ryans-world/SKILL.md
    ├── alex-cooper/SKILL.md
    ├── markiplier/SKILL.md
    ├── charli-damelio/SKILL.md
    ├── ms-rachel/SKILL.md
    ├── rebecca-zamolo/SKILL.md
    ├── khaby-lame/SKILL.md
    ├── stokes-twins/SKILL.md
    ├── ishowspeed/SKILL.md
    ├── jacksepticeye/SKILL.md
    ├── typical-gamer/SKILL.md
    ├── adam-waheed/SKILL.md
    └── dixie-damelio/SKILL.md
```

---

## Algorithm Reference

This repo's content formats and distribution strategies are aligned with the X algorithm:
👉 [https://github.com/xai-org/x-algorithm](https://github.com/xai-org/x-algorithm)

Key weights used in format design:
- Replies = 13.5x–27x the weight of likes
- Profile click + engagement = 24x a like
- 2+ minutes dwell time = 22x a like
- Native media gets algorithmic boost over text-only

---

## Contributing

This is a community resource. Contributions welcome.

- **Fork** the repo and add a new creator brain
- **Pull request** improvements to existing SKILL.md files
- **Open an issue** to request a creator or format library

### Adding a New Creator

1. Create a folder: `creators/[creator-slug]/`
2. Add a `SKILL.md` using the template below
3. Submit a pull request

### SKILL.md Template

```markdown
---
name: [creator-name]
description: [one line — who they are and what makes their content unique]
platforms: [YouTube, TikTok, X, Instagram, etc.]
niche: [entertainment / education / comedy / tech / lifestyle / etc.]
---

## Creator Overview
[2-3 sentences on who they are and why their content works]

## Platform-Specific Strategies
[Breakdown by platform — what they do differently on each one]

## Content Pillars
[The 3-5 recurring themes or content types they return to]

## Hook Formulas
[The specific ways they open content to stop the scroll/skip]

## Engagement Mechanics
[How they drive comments, shares, return visits]

## Tone & Voice
[How they speak — energy level, vocabulary, persona]

## Growth Levers
[What specifically drove their audience growth]

## Prompt Instructions
[How an LLM should channel this creator's brain]
```

---

## License

MIT — use it, build on it, ship it.

---

*Built for builders. Aligned with the algorithm. Open to everyone.*
