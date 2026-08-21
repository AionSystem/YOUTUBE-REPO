Aion: Forge & Fracture — YouTube Production Framework v0.3
0. Scope

This framework governs how a spec-build project becomes a five-part video series — from project selection through publish and review. It applies regardless of domain: game design doc, AI governance framework, technical spec, contract template. Current equipment constraint, stated explicitly: mobile phone and PC, free-tier tools only, free-tier AI usage only, no paid subscriptions until the channel funds them itself. This constraint is treated as part of the show's actual premise (Section 2), not hidden from it.

1. Series Structure

Every project becomes five videos, ~10 minutes each:

Part	Name	What has to be on screen
1	Idea Forming	Domain framing, the fusion pass — pulling reference points from multiple fields before any structure exists
2	Narrowing / Skeleton	Scope cuts, section headers, the document's bones taking shape
3	Build-Out	The skeleton getting filled in — actual drafting
4	Red Team	The finished draft run against the uploaded framework, gaps found, live revision
5	Proof of Function	What the finished spec is for, how it'd actually be used or tested

Part 4 is the hook — visible tension, something built then taken apart. Everything below protects that part's quality first.

2. Day-One / MVP Path

None of Sections 3–6 need to be finalized to publish video 1.

Project scope for a first build: small and real, not large and reused. A single game system (one mechanic, not a full GDD), a single-clause contract template, a short 1–2 page policy memo — something buildable and red-teamable from scratch, on camera, inside the free-tier AI budget described below. Building live is the actual differentiator from a generic consulting pitch; narrating a large audit already done doesn't show the same thing.

Minimum bar for a publishable video 1: audio-free screen capture, basic cuts, one caption or callout at the strongest moment.

2.5. Free-Tier Budget Reality (new)

Claude's usage limit is token-based and tracked over a rolling 5-hour window, not a flat message count. Long conversations, large uploaded reference files, and lengthy prompts consume the budget far faster than short, focused exchanges — this is documented directly in Anthropic's own help center, not a guess. Practical implications:

Keep session prompts and any uploaded reference material lean. A framework file re-uploaded every session costs real budget; keep it in a Project or reference it by name once established rather than re-pasting it.
Project scope (Section 2) should be small enough to complete its AI exchanges inside one or two 5-hour windows, not stretched across a week fighting the reset.
One AI session naturally produces roughly one video part's worth of usable material. This isn't a constraint to defeat — it's a natural pacing mechanism. A five-part series recorded one session per day, spread across a work week, already matches a healthy release cadence without forcing anything.
Claude Pro (~5x free-tier usage, $20/month per Anthropic's current pricing) is the threshold worth knowing about for when the channel funds itself — not a requirement to start.
3. Recording Workflow

Free tools:

PC screen capture: OBS Studio (free) or the OS's built-in recorder (Windows Game Bar, macOS's built-in screen recording).
Phone's role in this format is secondary — the actual work happens on the PC.

Work in the actual part-sized unit where possible. Keep the chat and any reference document visible on screen. No voice.

4. Editing Workflow

AI auto-highlight tools key off speech and won't find the good moments in voiceless text footage. Selection stays manual, in CapCut free tier. Stick to the free feature set.

Every video gets at least one on-screen callout or caption at its strongest moment — for Part 4, almost always the exact instant the red team catches something.
Logo overlay and royalty-free/no-copyright music, both free-tier compatible, added once a source is picked.
Visual template (font, color treatment, lower-third) stays fixed once built — tied to the existing indigo/cyan/periwinkle AionSystem palette. Not a blocker for video 1.
5. Naming and Metadata

Avoid "AI red teaming" unqualified — it's a claimed term for LLM jailbreaking content, a different field. Use "structural red team," "spec red team," or "adversarial structural analysis."

Title template: [Project Name] — Part [N]: [Part Name] Thumbnail rule: lead with a Part 4 moment even on earlier parts' thumbnails.

6. Project Selection Rule (video 2 onward)

Don't run the same domain twice in a row once rotation starts. Rotate across domains to protect the "any domain" positioning. This activates at video 2; video 1's project is governed by Section 2.

7. Publishing Cadence

Default: one part per week, naturally matching one AI session per day (Section 2.5). Adjust once Section 8's log shows real production time per video.

8. Tracking Log
Date published	Project	Part	Views (7-day)	Avg. view duration	What worked	What didn't
						
9. Failure Modes

Editing debt. Recording long and loose on the assumption CapCut will save it in post.

Term collision. Using "AI red team" unqualified in titles/tags.

Domain lock creeping back in. Letting rotation slide because one domain is easier to line up.

Part 1 drop-off. The least dramatic part also being the first thing a new viewer sees.

System-completeness as a delay tactic. Treating an unfinished template or undecided cadence as a reason video 1 can't go out yet.

Fighting the free-tier rhythm instead of using it. Trying to force a week's worth of AI exchanges into one sitting, then treating the reset as an obstacle, instead of letting one session per day become one video part per day.

10. Open Questions

Whether Part 1 needs a cold-open hook. Whether title/thumbnail should reveal the red-team finding in advance — decide by small test once more than one series is published. Whether project scope needs a hard cap (e.g., under a certain word count) stated explicitly once real budget data from Section 8 exists.