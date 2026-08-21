# Metadata Templates

## Purpose

This folder contains templates and records for video metadata (titles, tags, descriptions).

## Title Template

```
[Project Name] — Part [N]: [Part Name]
```

**Examples:**
- `Game Design Doc — Part 1: Idea Forming`
- `RV Build System — Part 4: Red Team`
- `Policy Memo — Part 5: Proof of Function`

## Tag Strategy

**Target the domain's existing search space**, not just the channel's audience.

### Core Tags (All Videos)
- AION Forge and Fracture
- Sheldon K Salmon
- [Series identifier]

### Domain-Specific Tags
- Varies by episode domain
- Research what that domain searches for
- Example for game design: "game design document", "GDD template", "indie game dev"
- Example for RV: "RV custom build", "RV renovation", "van life setup"

### Process Tags
- Structural red team
- Adversarial analysis
- Spec building
- [Avoid: "AI red teaming" unqualified]

## Description Template

```markdown
[Hook - lead with Part 4 moment even on earlier parts]

In this [Part N] of AION: Forge & Fracture, we're building [domain/project] from scratch using a five-part pipeline:
1. Idea Forming
2. Narrowing / Skeleton
3. Build-Out
4. Red Team ← This is Part [N]
5. Proof of Function

[Domain-specific context - speak to THIS domain's audience]

[Classification note if high-stakes]
⚠️ This domain touches [safety/legal/health/financial]. This is a rapid draft built on camera — treat it as a starting point, not professional guidance.

---

**About AION: Forge & Fracture:**
A screen-recorded build series where real specs, frameworks, and design docs are built from scratch in different domains every episode. No face, no voice — the build carries the video.

**Channel:** Sheldon K. Salmon
**Subscribe:** https://youtube.com/@SheldonKSalmon

#AIONForgeAndFracture #SheldonKSalmon #[DomainTag1] #[DomainTag2]
```

## Thumbnail Rule

**Lead with a Part 4 moment even on earlier parts' thumbnails.**

The red team catch is the hook — use it to draw viewers in from Part 1.

## Files

- `title_log.md` - Record of all titles used
- `tag_bank.md` - Reusable tag collections by domain type
- `description_archive/` - Past video descriptions

---

*Metadata should make each episode findable by the domain's own audience, not just existing channel viewers.*
