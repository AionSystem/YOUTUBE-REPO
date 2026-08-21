# AION: Forge & Fracture - Series Documentation

**Channel:** Sheldon K. Salmon  
**Channel URL:** https://youtube.com/@SheldonKSalmon  
**Series:** AION: Forge & Fracture

## Overview

Aion: Forge & Fracture is a screen-recorded build series featuring real specs, frameworks, and design docs built from scratch, live, in a different domain every episode. Domains are selected via a "domain roulette" system rather than a fixed niche.

### Core Premise

- **No face, no voice** — The build itself carries the video through silent screen capture
- **On-screen text/captions** and visual structure communicate all information
- **Five-part arc** for every project regardless of domain
- **Domain rotation** ensures cross-niche reach and prevents audience fatigue

## The Five-Part Pipeline

| Part | Name | Purpose |
|------|------|---------|
| 1 | Idea Forming | Domain framing, fusion pass — pulling reference points from multiple fields |
| 2 | Narrowing / Skeleton | Scope cuts, section headers, document bones taking shape |
| 3 | Build-Out | Skeleton gets filled in — actual drafting |
| 4 | Red Team | Finished draft tested against framework, gaps found, live revision |
| 5 | Proof of Function | What the finished spec is for, how it'd actually be used or tested |

**Part 4 (Red Team) is the hook** — visible tension, something built then taken apart.

## Domain Classification

### Low-Stakes Domains
- No real safety, health, legal, structural, or financial consequence if output is wrong
- Examples: games, general productivity, hobbies, entertainment, creative domains
- **Action:** Build and sell freely

### High-Stakes Domains
- Touches safety, structural/mechanical work, health, legal, financial decisions, livelihood
- **Action:** Still film it (honest content), but if offered as download:
  - Label explicitly as rapid draft / starting point
  - State clearly on product page it's not professional guidance

## Repository Structure

```
Youtube_Repo/
├── .github/                    # GitHub configuration (issues, workflows)
├── assets/                     # Media assets
│   ├── branding/               # Logos, color palettes, style guides
│   ├── music/                  # Royalty-free audio tracks
│   ├── templates/              # Video templates, overlays
│   └── thumbnails/             # Thumbnail source files
├── config/                     # Configuration files
├── docs/                       # General documentation
├── scripts/                    # Automation scripts
├── series/
│   └── AION_Forge_and_Fracture/
│       ├── domain_roulette/    # Domain selection records
│       ├── documentation/      # Series-level docs
│       ├── episodes/           # Per-episode folders (EP001, EP002, etc.)
│       ├── metadata/           # Titles, tags, descriptions
│       ├── production_assets/  # Raw footage, project files
│       └── red_team_reports/   # Red team findings archive
├── tools/                      # Utility tools
└── README.md                   # This file
```

## Production Constraints

- **Equipment:** Mobile phone and PC only
- **Tools:** Free-tier software only
- **AI Usage:** Free-tier AI budgets only
- **No paid subscriptions** until channel funds them itself

This constraint is part of the show's premise, not hidden from it.

## Free-Tier AI Budget Reality

Claude's usage limit is token-based over a rolling 5-hour window:

- Keep session prompts and uploaded references lean
- Project scope should fit inside 1-2 AI windows
- One AI session ≈ one video part's worth of material
- Five-part series = five sessions across a work week (natural pacing)

## Publishing Cadence

**Default:** One part per week (matches one AI session per day)

## Key Rules

1. **No repeating domains back-to-back** (Section 6 of framework)
2. **Never use "AI red teaming" unqualified** — use "structural red team," "spec red team," or "adversarial structural analysis"
3. **Part 4 must find something real** — no soft-pedaling flaws
4. **Titles target domain's search space** — reach that domain's audience, not just channel's

## Failure Modes to Avoid

- Editing debt (recording long, expecting post to save it)
- Term collision (using "AI red team" unqualified)
- Domain lock creeping in
- Part 1 drop-off (least dramatic part is first impression)
- System-completeness as delay tactic
- Fighting the free-tier rhythm

## Getting Started

For new episode development, see:
- `/series/AION_Forge_and_Fracture/domain_roulette/` - Domain selection process
- `/series/AION_Forge_and_Fracture/episodes/` - Episode-specific work
- `/docs/` - Framework documentation

---

*This repository follows enterprise-grade AAA standards with placeholder files for scalable production.*
