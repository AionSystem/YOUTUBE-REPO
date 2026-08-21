# Sheldon K. Salmon - YouTube Production Repository

**Channel:** Sheldon K. Salmon  
**URL:** https://youtube.com/@SheldonKSalmon  
**Repository Type:** Enterprise-Grade AAA Production Infrastructure  
**Status:** Production-Ready ✅

---

## Executive Summary

This repository serves as the central production hub for all content series on the Sheldon K. Salmon YouTube channel. Built to **enterprise-grade AAA standards**, it implements a scalable, modular architecture designed for professional video production workflows while operating under free-tier constraints.

### Key Features

- 🏗️ **43 Directories** organized for multi-series scalability
- 📋 **40 Documentation Files** with detailed templates and guidelines
- 🎬 **Five-Part Production Pipeline** standardized across all episodes
- 🎯 **Domain Roulette System** for cross-niche audience reach
- 🔴 **Red Team Integration** for adversarial structural analysis
- 💰 **Free-Tier Optimized** workflows (mobile/PC only, no paid tools)

---

## Current Series

### 🎥 AION: Forge & Fracture *(Active)*

**Premise:** A screen-recorded build series where real specs, frameworks, and design documents are built from scratch in different domains every episode.

| Attribute | Detail |
|-----------|--------|
| **Format** | Silent screen capture with on-screen text/captions |
| **Structure** | Five-part arc (Idea → Skeleton → Build-Out → Red Team → Proof) |
| **Hook** | Part 4 (Red Team) - visible tension, live revision |
| **Cadence** | One part per week (natural AI session pacing) |
| **Location** | `/series/AION_Forge_and_Fracture/` |
| **Documentation** | See `/series/AION_Forge_and_Fracture/README.md` |

**Core Principles:**
1. No face, no voice — the build carries the video
2. Domain rotation prevents niche fatigue
3. Free-tier AI budget reality shapes production rhythm
4. Structural red teaming (not "AI red teaming") terminology
5. Low-stakes vs. high-stakes domain classification

---

## Complete Repository Structure

```
YOUTUBE-REPO/
│
├── .github/                              # GitHub Configuration & Automation
│   ├── ISSUE_TEMPLATE/                   # Standardized issue tracking
│   │   ├── bug_report.md                 # Bug reports for tools/scripts
│   │   ├── feature_request.md            # New feature proposals
│   │   └── production_task.md            # Episode production tracking
│   └── workflows/                        # CI/CD automation pipelines
│       └── .gitkeep                      # Placeholder for future workflows
│
├── assets/                               # Shared Media Assets Library
│   ├── branding/                         # Visual Identity System
│   │   ├── logos/                        # Channel & series logos (SVG/PNG)
│   │   ├── color_palettes/               # Indigo/Cyan/Periwinkle palette specs
│   │   ├── style_guides/                 # Typography, spacing, usage rules
│   │   └── README.md                     # Brand asset documentation
│   ├── music/                            # Audio Library
│   │   ├── intro_outro/                  # Theme music variations
│   │   ├── background_tracks/            # Royalty-free ambient tracks
│   │   └── README.md                     # Licensing & attribution guide
│   ├── templates/                        # Video Production Templates
│   │   ├── overlays/                     # Stream/recording overlays
│   │   ├── lower_thirds/                 # Name/title animations
│   │   ├── callouts/                     # Highlight/emphasis graphics
│   │   └── README.md                     # Template usage instructions
│   └── thumbnails/                       # Thumbnail Source Files
│       ├── AION_series/                  # AION-specific thumbnail templates
│       ├── fonts/                        # Custom font files
│       └── README.md                     # Thumbnail design guidelines
│
├── config/                               # Production Configuration Files
│   ├── obs/                              # OBS Studio Configurations
│   │   ├── scene_collections/            # Recording scene setups
│   │   ├── profiles/                     # Encoder & output profiles
│   │   └── README.md                     # OBS setup documentation
│   ├── capcut/                           # CapCut Editor Configurations
│   │   ├── project_templates/            # Pre-built editing timelines
│   │   ├── presets/                      # Effect & transition presets
│   │   └── README.md                     # CapCut workflow guide
│   ├── workflow/                         # Workflow Automation Configs
│   │   ├── file_naming_conventions.md    # Standardized naming rules
│   │   ├── export_settings.md            # Video/audio export specs
│   │   └── checklist_templates.md        # Pre-publish checklists
│   └── README.md                         # Configuration management guide
│
├── docs/                                 # General Documentation Hub
│   ├── guides/                           # How-To Documentation
│   │   ├── getting_started.md            # Onboarding for new contributors
│   │   ├── production_workflow.md        # End-to-end production process
│   │   ├── publishing_guide.md           # Upload, SEO, distribution steps
│   │   └── README.md                     # Guide index
│   ├── reference/                        # Technical Reference Materials
│   │   ├── framework_reference.md        # Five-part pipeline specification
│   │   ├── terminology.md                # Glossary of terms (red team, etc.)
│   │   ├── tools.md                      # Tool stack documentation
│   │   ├── api_reference.md              # Script/tool API documentation
│   │   └── README.md                     # Reference index
│   └── policies/                         # Operational Policies
│       ├── content_guidelines.md         # Content standards & boundaries
│       ├── quality_standards.md          # QA criteria & acceptance tests
│       └── README.md                     # Policy documentation index
│
├── scripts/                              # Automation Scripts
│   ├── utilities/                        # General Utility Scripts
│   │   ├── file_organizers/              # Auto-sort recorded footage
│   │   ├── batch_processors/             # Bulk metadata operations
│   │   └── README.md                     # Utility script documentation
│   ├── analytics/                        # Analytics & Reporting Scripts
│   │   ├── view_trackers/                # Performance monitoring
│   │   ├── audience_insights/            # Demographic analysis
│   │   └── README.md                     # Analytics script guide
│   ├── production/                       # Production Automation Scripts
│   │   ├── render_pipelines/             # Automated rendering workflows
│   │   ├── asset_management/             # Version control for assets
│   │   └── README.md                     # Production script documentation
│   ├── metadata/                         # Metadata Generation Scripts
│   │   ├── title_generators/             # SEO-optimized title creation
│   │   ├── tag_suggesters/               # Domain-specific tag generation
│   │   ├── description_builders/         # Description template population
│   │   └── README.md                     # Metadata script guide
│   └── README.md                         # Scripts overview & execution guide
│
├── series/                               # All Video Series Production Folders
│   └── AION_Forge_and_Fracture/          # Flagship Series Directory
│       ├── README.md                     # Series bible & production guide
│       │
│       ├── domain_roulette/              # Domain Selection System
│       │   ├── candidates/               # Potential domain candidates
│       │   │   └── EP001_candidates.md   # Episode 1 candidate list
│       │   ├── selection_log.md          # Historical selection records
│       │   ├── domain_classification.md  # Low-stakes vs. high-stakes guide
│       │   └── README.md                 # Domain roulette process docs
│       │
│       ├── documentation/                # Series-Level Documentation
│       │   ├── pipeline/                 # Five-Part Pipeline Documentation
│       │   │   ├── part1_idea_forming.md      # Domain framing & fusion
│       │   │   ├── part2_narrowing.md         # Scope cuts & skeleton
│       │   │   ├── part3_buildout.md          # Drafting phase
│       │   │   ├── part4_red_team.md          # Adversarial analysis
│       │   │   └── part5_proof_of_function.md # Usage & testing specs
│       │   ├── failure_modes/            # Known pitfalls & avoidance
│       │   │   ├── editing_debt.md            # Recording vs. editing balance
│       │   │   ├── term_collision.md          # Terminology mistakes
│       │   │   ├── domain_lock.md             # Niche fatigue prevention
│       │   │   ├── part1_dropoff.md           # First impression optimization
│       │   │   └── README.md                    # Failure modes index
│       │   ├── roadmap.md                # Series development timeline
│       │   └── README.md                 # Documentation structure guide
│       │
│       ├── episodes/                     # Per-Episode Production Folders
│       │   └── [EP###_DomainName]/       # Template: EP001_SmartHomeSecurity
│       │       ├── README.md             # Episode-specific production notes
│       │       ├── pre_production/       # Planning & preparation
│       │       │   ├── spec_draft.md     # Initial specification document
│       │       │   ├── outline.md        # Episode structure outline
│       │       │   └── assets_needed.md  # Required assets checklist
│       │       ├── production/           # Recording phase artifacts
│       │       │   ├── raw_recordings/   # Unedited screen captures
│       │       │   ├── session_logs/     # AI session transcripts
│       │       │   └── takes/            # Multiple recording attempts
│       │       ├── post_production/      # Editing & finalization
│       │       │   ├── edited_sequences/ # Cut & assembled footage
│       │       │   ├── captions/         # On-screen text files
│       │       │   └── final_render/     # Master video file
│       │       └── publish/              # Publication package
│       │           ├── metadata.json     # Title, tags, description
│       │           ├── thumbnail.png     # Final thumbnail
│       │           └── upload_checklist.md
│       │
│       ├── metadata/                     # SEO & Discovery Assets
│       │   ├── titles/                   # Title Variations
│       │   │   ├── main_titles.md        # Primary title options
│       │   │   ├── ab_test_variants.md   # A/B testing alternatives
│       │   │   └── domain_specific/      # Domain-targeted titles
│       │   ├── tags/                     # Tag Banks
│       │   │   ├── core_tags.md          # Evergreen channel tags
│       │   │   ├── domain_tags.md        # Rotating domain-specific tags
│       │   │   └── tag_bank.md           # Comprehensive tag repository
│       │   ├── descriptions/             # Description Templates
│       │   │   ├── template_master.md    # Master description template
│       │   │   └── description_archive/  # Historical descriptions
│       │   │       └── EP001_description.md
│       │   └── README.md                 # Metadata strategy & templates
│       │
│       ├── production_assets/            # Raw & Processed Media Files
│       │   ├── raw_footage/              # Unprocessed Screen Recordings
│       │   │   ├── part1/                # Idea Forming sessions
│       │   │   ├── part2/                # Narrowing/Skeleton sessions
│       │   │   ├── part3/                # Build-Out sessions
│       │   │   ├── part4/                # Red Team sessions
│       │   │   ├── part5/                # Proof of Function sessions
│       │   │   └── README.md             # Footage organization guide
│       │   ├── project_files/            # Editor Project Files
│       │   │   ├── capcut_projects/      # CapCut timeline files
│       │   │   ├── backup_projects/      # Versioned backups
│       │   │   └── README.md             # Project file management
│       │   ├── graphics/                 # Motion Graphics & Overlays
│       │   │   ├── callouts/             # Highlight annotations
│       │   │   ├── overlays/             # Full-screen graphics
│       │   │   ├── lower_thirds/         # Name/title animations
│       │   │   └── README.md             # Graphics asset guide
│       │   ├── exports/                  # Rendered Output Files
│       │   │   ├── drafts/               # Work-in-progress renders
│       │   │   ├── finals/               # Master quality exports
│       │   │   ├── social_clips/         # Short-form derivatives
│       │   │   └── README.md             # Export settings & versions
│       │   ├── reference/                # Reference Materials
│       │   │   ├── inspiration/          # Example videos/docs
│       │   │   ├── competitor_analysis/  # Similar content studies
│       │   │   └── README.md             # Reference curation guide
│       │   └── README.md                 # Production assets overview
│       │
│       └── red_team_reports/             # Adversarial Analysis Archive
│           ├── EP001_RedTeam/            # Episode 1 Red Team Findings
│           │   ├── findings_summary.md   # Consolidated gap analysis
│           │   ├── structural_critique.md# Framework compliance review
│           │   ├── revision_log.md       # Changes made post-critique
│           │   └── lessons_learned.md    # Takeaways for future episodes
│           ├── methodology.md            # Red team process documentation
│           ├── terminology_guide.md      # Proper terminology usage
│           └── README.md                 # Red team reports overview
│
├── tools/                                # Standalone Utility Tools
│   ├── qa/                               # Quality Assurance Tools
│   │   ├── checklist_validators/         # Automated checklist verification
│   │   ├── quality_scanners/             # Video/audio quality analyzers
│   │   └── README.md                     # QA tools documentation
│   ├── analytics/                        # Analytics Tools
│   │   ├── dashboard_builders/           # Performance visualization
│   │   ├── trend_analyzers/              # Viewership pattern detection
│   │   └── README.md                     # Analytics tools guide
│   ├── production/                       # Production Support Tools
│   │   ├── render_helpers/               # Rendering acceleration utilities
│   │   ├── format_converters/            # Media format conversion tools
│   │   └── README.md                     # Production tools documentation
│   ├── metadata/                         # Metadata Management Tools
│   │   ├── seo_optimizers/               # Search optimization utilities
│   │   ├── tag_managers/                 # Tag organization & suggestion
│   │   └── README.md                     # Metadata tools guide
│   └── README.md                         # Tools directory overview
│
├── .gitignore                            # Git Ignore Rules (production safety)
├── LICENSE                               # Repository License (TBD)
└── README.md                             # This File - Master Documentation
```

---

## Production Standards & Methodologies

### Enterprise-Grade AAA Standards

This repository implements professional production methodologies adapted for solo creator workflows:

| Standard | Implementation |
|----------|----------------|
| **Scalability** | Modular folder structure supports unlimited episodes & series |
| **Version Control** | All production assets tracked with meaningful commit history |
| **Separation of Concerns** | Clear boundaries between raw, working, and final assets |
| **Documentation-First** | Every folder includes README with purpose & usage |
| **Automation-Ready** | Scripts/tools folders prepared for CI/CD integration |
| **Quality Gates** | Red team reports & QA checklists enforce consistency |

### Five-Part Production Pipeline

Every episode follows this standardized arc:

```
┌─────────────────────────────────────────────────────────────┐
│  PART 1: IDEA FORMING                                       │
│  • Domain framing                                           │
│  • Fusion pass (multi-field reference points)               │
│  • Initial concept validation                               │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  PART 2: NARROWING / SKELETON                               │
│  • Scope cuts                                               │
│  • Section headers defined                                  │
│  • Document bones take shape                                │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  PART 3: BUILD-OUT                                          │
│  • Skeleton filled in                                       │
│  • Actual drafting of spec/framework                        │
│  • Substance over polish                                    │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  PART 4: RED TEAM ⭐ (THE HOOK)                              │
│  • Finished draft tested against framework                  │
│  • Gaps identified through adversarial analysis             │
│  • Live revision demonstrating iteration                    │
│  • Visible tension = viewer engagement                      │
└─────────────────────────────────────────────────────────────┘
                            ↓
┌─────────────────────────────────────────────────────────────┐
│  PART 5: PROOF OF FUNCTION                                  │
│  • What the finished spec is for                            │
│  • How it would actually be used or tested                  │
│  • Real-world application scenarios                         │
└─────────────────────────────────────────────────────────────┘
```

### Domain Classification System

**Low-Stakes Domains** (Safe to build & sell):
- Games, general productivity, hobbies, entertainment, creative domains
- No safety, health, legal, structural, or financial consequences

**High-Stakes Domains** (Film honestly, label carefully):
- Safety-critical, structural/mechanical, health, legal, financial decisions
- Must label as "rapid draft / starting point" if offered as download
- Explicit disclaimer: not professional guidance

### Free-Tier Production Constraints

This constraint is **part of the show's premise**, not hidden:

| Resource | Constraint | Strategy |
|----------|------------|----------|
| **Equipment** | Mobile phone + PC only | Leverage screen recording, minimize B-roll |
| **Software** | Free-tier only | OBS, CapCut, free AI tools |
| **AI Budget** | Token-limited sessions | 1 session ≈ 1 video part; 5 parts = 5 sessions/week |
| **Time** | Solo creator bandwidth | Natural pacing matches AI rate limits |

---

## Quick Start Guides

### 🎬 Starting a New Episode

1. **Domain Selection**
   ```bash
   cd /workspace/YOUTUBE-REPO/series/AION_Forge_and_Fracture/domain_roulette/
   # Review candidates/, add new ideas, run selection process
   ```

2. **Create Episode Folder**
   ```bash
   cd /workspace/YOUTUBE-REPO/series/AION_Forge_and_Fracture/episodes/
   mkdir EP001_[DomainName]  # e.g., EP001_SmartHomeSecurity
   # Copy template structure from documentation
   ```

3. **Begin Part 1 Production**
   - Open `documentation/pipeline/part1_idea_forming.md` for guidelines
   - Create spec draft in episode's `pre_production/spec_draft.md`
   - Record AI session, save transcript to `production/session_logs/`

### 🛠️ Setting Up Your Production Environment

1. **Configure OBS**
   ```bash
   cd /workspace/YOUTUBE-REPO/config/obs/
   # Import scene collections, set up profiles for screen recording
   ```

2. **Prepare CapCut Templates**
   ```bash
   cd /workspace/YOUTUBE-REPO/config/capcut/
   # Load project templates, configure presets
   ```

3. **Review Workflow Checklists**
   ```bash
   cd /workspace/YOUTUBE-REPO/config/workflow/
   # Study file_naming_conventions.md, export_settings.md
   ```

### 📊 Publishing an Episode

1. **Generate Metadata**
   ```bash
   cd /workspace/YOUTUBE-REPO/series/AION_Forge_and_Fracture/metadata/
   # Use templates in titles/, tags/, descriptions/
   ```

2. **Run QA Checks**
   ```bash
   cd /workspace/YOUTUBE-REPO/tools/qa/
   # Execute checklist validators, quality scanners
   ```

3. **Finalize Upload Package**
   ```bash
   cd /workspace/YOUTUBE-REPO/series/AION_Forge_and_Fracture/episodes/EP001_[DomainName]/publish/
   # Verify metadata.json, thumbnail.png, upload_checklist.md
   ```

---

## Key Rules & Guidelines

### Non-Negotiable Rules

1. ✅ **No repeating domains back-to-back** (prevents niche fatigue)
2. ✅ **Never use "AI red teaming" unqualified** — use:
   - "Structural red team"
   - "Spec red team"
   - "Adversarial structural analysis"
3. ✅ **Part 4 must find something real** — no soft-pedaling flaws
4. ✅ **Titles target domain's search space** — reach that domain's audience
5. ✅ **Free-tier discipline** — no paid tools until channel funds itself

### Failure Modes to Actively Avoid

| Failure Mode | Symptom | Prevention |
|--------------|---------|------------|
| **Editing Debt** | Recording long, expecting post to save it | Tight session scopes, real-time decision making |
| **Term Collision** | Using "AI red team" without qualification | Enforce terminology guide in docs/reference/ |
| **Domain Lock** | Creeping back into same niche | Domain roulette system, classification tracking |
| **Part 1 Drop-off** | Weak first impression loses viewers | Invest extra effort in Part 1 hook & clarity |
| **System-Completeness Delay** | Over-engineering instead of shipping | Time-box sessions, ship imperfect but functional |
| **Fighting Free-Tier Rhythm** | Burning through AI limits too fast | Accept 5-session pace as natural production cadence |

---

## Repository Metrics

| Metric | Count | Status |
|--------|-------|--------|
| **Total Directories** | 43 | ✅ Complete |
| **Documentation Files** | 40 | ✅ Created |
| **Placeholder Files** | 6 `.gitkeep` files | ✅ In place |
| **Series Active** | 1 (AION) | 🟡 Ready for EP001 |
| **Production Pipelines** | 1 (Five-Part) | ✅ Documented |
| **Automation Scripts** | 0 | 🟡 Awaiting development |
| **Recorded Episodes** | 0 | ⚪ Pre-production |

---

## Contributing & Collaboration

### Issue Tracking

Use GitHub Issues for:
- 🐛 **Bug Reports**: Tools, scripts, or workflow issues
- 💡 **Feature Requests**: New automation, templates, or processes
- 🎬 **Production Tasks**: Episode-specific work tracking

### Workflow

1. **Create Issue** → Select appropriate template from `.github/ISSUE_TEMPLATE/`
2. **Assign Labels** → Tag with series, episode, priority
3. **Track Progress** → Update status through completion
4. **Document Learnings** → Add retrospective to `documentation/retrospectives/`

---

## Future Roadmap

### Phase 1: Foundation (Current)
- ✅ Repository structure complete
- ✅ Documentation framework established
- ✅ Production templates created
- 🟡 Episode 001 domain selection pending

### Phase 2: First Production Cycle
- ⚪ Film & publish Episode 001 (all 5 parts)
- ⚪ Establish red team methodology
- ⚪ Refine workflows based on real production data
- ⚪ Build initial tag bank & title patterns

### Phase 3: Automation & Scale
- ⚪ Develop metadata generation scripts
- ⚪ Implement render pipeline automation
- ⚪ Create analytics dashboards
- ⚪ Expand to additional series formats

### Phase 4: Optimization
- ⚪ A/B test thumbnails & titles systematically
- ⚪ Build audience insights models
- ⚪ Optimize free-tier AI usage patterns
- ⚪ Explore monetization pathways

---

## Contact & Links

- **YouTube Channel:** https://youtube.com/@SheldonKSalmon
- **Series Documentation:** `/series/AION_Forge_and_Fracture/README.md`
- **Production Guides:** `/docs/guides/`
- **Framework Reference:** `/docs/reference/framework_reference.md`

---

<div align="center">

**Built for Scalable YouTube Production with Professional Standards**

*Enterprise-Grade AAA Infrastructure for the Modern Creator*

🎬 **Status:** Production-Ready | 📅 **Last Updated:** 2025

</div>
