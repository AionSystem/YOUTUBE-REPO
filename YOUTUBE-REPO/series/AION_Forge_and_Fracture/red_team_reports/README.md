# Red Team Reports Archive

## Purpose

This folder contains all structural red team findings from Part 4 of each episode.

## Standing Rules for Red Team (Part 4)

1. **Must find something real** — No soft-pedaling flaws to protect the impressive-speed story
2. **Use qualified terminology:**
   - ✅ "Structural red team"
   - ✅ "Spec red team"
   - ✅ "Adversarial structural analysis"
   - ❌ "AI red teaming" (unqualified — this is LLM jailbreaking content)

3. **Visible tension** — The moment the red team catches something should be a highlighted callout in the video

## Report Structure

Each red team report should include:

```markdown
# [Episode ID] - Red Team Report

## Domain
[The domain being tested]

## Original Draft Summary
[Brief description of what was built]

## Red Team Methodology
[Framework or approach used for adversarial analysis]

## Findings

### Critical Flaws
- [Flaw 1 with explanation]
- [Flaw 2 with explanation]

### Moderate Issues
- [Issue 1]
- [Issue 2]

### Minor Concerns
- [Concern 1]
- [Concern 2]

## Revisions Made
[What was changed in response to findings]

## Remaining Limitations
[What couldn't be fixed and why]

## Classification Impact
[If high-stakes domain: explicit labeling applied]
```

## Files

- `EP001_*/` - Per-episode red team reports
- `framework_reference.md` - The red team framework used for analysis
- `findings_summary.md` - Aggregated findings across all episodes

---

*Part 4 is the hook of the series. A red team that doesn't break anything isn't credible.*
