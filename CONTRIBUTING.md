# How to Contribute to content-skills

Thank you for contributing! This repository is a community resource — your additions make it more valuable for everyone.

---

## Ways to Contribute

### 1. Add a New Creator Brain
Submit a `SKILL.md` for a creator not yet in the repo.

### 2. Improve an Existing SKILL.md
If you see something outdated, incomplete, or wrong — fix it.

### 3. Add a New Format Library
Create a new file in `/formats/` for a platform not yet covered (LinkedIn, YouTube, Instagram, TikTok, etc.)

### 4. Report Issues
Open a GitHub Issue if you notice inaccurate information, outdated platform strategies, or broken links.

---

## Creator SKILL.md Template

```markdown
---
name: [creator-slug]
description: [one line — who they are and what makes their content unique]
platforms: [platform1, platform2, ...]
niche: [niche / content category]
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

## Format Library Template

```markdown
---
name: [platform]-formats
description: [what this covers]
platforms: [platform]
algorithm-reference: [link if applicable]
last-updated: [date]
---

# [Platform] Content Formats

## Algorithm Context
[Key signals and weights]

## Format 1: [Name]
[Template, why it works, example]

...

## Prompt Instructions for LLMs
[How to apply this format library]
```

---

## Quality Guidelines

- **Be specific** — vague advice ("post good content") has no value. What specifically does this creator do?
- **Be platform-accurate** — strategies for YouTube don't apply to TikTok. Separate them.
- **Be honest about what works** — cite real patterns, not aspirational advice
- **Keep it LLM-friendly** — write in a way that an LLM can actually use as a system prompt
- **Keep SKILL.md files self-contained** — they should work when copy-pasted into any LLM context

---

## Pull Request Process

1. Fork the repo
2. Create a branch: `git checkout -b creator/[creator-name]`
3. Add your `SKILL.md` file
4. Submit a PR with a brief description of what you're adding and why

---

## Code of Conduct

- Respect creators — critique their strategies, not their character
- Keep content professional and constructive
- No promotional content disguised as creator profiles
- Contributions should serve users of this repo, not promote products

---

*Built for builders. Open to everyone.*
