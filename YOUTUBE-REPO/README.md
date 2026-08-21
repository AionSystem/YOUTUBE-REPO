# Sheldon K. Salmon - YouTube Channel Repository

**Channel:** Sheldon K. Salmon  
**URL:** https://youtube.com/@SheldonKSalmon

## Welcome

This repository houses the production infrastructure for all content series on the Sheldon K. Salmon YouTube channel.

## Current Series

### AION: Forge & Fracture

A screen-recorded build series where real specs, frameworks, and design docs are built from scratch in different domains every episode.

- **Series Location:** `/series/AION_Forge_and_Fracture/`
- **Documentation:** See `/series/AION_Forge_and_Fracture/README.md`

## Repository Structure

```
Youtube_Repo/
├── .github/                    # GitHub configuration
│   ├── ISSUE_TEMPLATE/         # Issue templates for tracking
│   └── workflows/              # CI/CD automation
├── assets/                     # Shared media assets
│   ├── branding/               # Logos, color palettes, style guides
│   ├── music/                  # Royalty-free audio tracks
│   ├── templates/              # Video templates, overlays
│   └── thumbnails/             # Thumbnail source files
├── config/                     # Configuration files
├── docs/                       # General documentation
├── scripts/                    # Automation scripts
├── series/                     # All video series
│   └── AION_Forge_and_Fracture/
│       ├── domain_roulette/    # Domain selection records
│       ├── documentation/      # Series-level docs
│       ├── episodes/           # Per-episode folders
│       ├── metadata/           # Titles, tags, descriptions
│       ├── production_assets/  # Raw footage, project files
│       └── red_team_reports/   # Red team findings archive
├── tools/                      # Utility tools
├── README.md                   # This file
└── [series-specific README]    # Series documentation
```

## Quick Start

### For New Episodes

1. Navigate to `/series/AION_Forge_and_Fracture/domain_roulette/`
2. Follow the domain selection process
3. Create new episode folder in `/series/AION_Forge_and_Fracture/episodes/`

### For Production

- **Recording:** See production workflow in series documentation
- **Editing:** Assets stored in `/assets/`
- **Metadata:** Templates in `/series/AION_Forge_and_Fracture/metadata/`

## Production Standards

This repository follows enterprise-grade AAA standards:

- Organized folder structure for scalability
- Placeholder files for consistent workflows
- Clear separation of concerns
- Version-controlled production assets

## Contributing

All production work is tracked through GitHub issues and organized by series.

---

*Built for scalable YouTube production with professional standards.*
