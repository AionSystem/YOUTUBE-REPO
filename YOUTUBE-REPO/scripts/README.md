# Scripts and Automation

## Purpose

This folder contains scripts for automating production workflows.

## Script Categories

### `/production/`
- Recording automation
- File organization
- Batch processing

### `/metadata/`
- Title generation helpers
- Tag suggestions
- Description templates

### `/analytics/`
- View tracking
- Performance analysis
- Report generation

### `/utilities/`
- File renaming
- Backup scripts
- Cleanup tools

## Script Standards

### Language Preference
1. Python (cross-platform)
2. Bash (system utilities)
3. Node.js (if needed for specific tools)

### Requirements
- Document dependencies in `requirements.txt` per script folder
- Include usage examples in script headers
- Handle errors gracefully
- Log actions for debugging

### Example Structure
```
scripts/
├── production/
│   ├── organize_footage.py
│   └── batch_export.py
├── metadata/
│   ├── generate_description.py
│   └── tag_helper.py
├── analytics/
│   └── view_tracker.py
├── utilities/
│   ├── rename_files.py
│   └── backup.sh
└── README.md
```

## Getting Started

1. Review existing scripts before creating new ones
2. Test scripts on non-production data first
3. Document any manual steps that remain
4. Update this README when adding new scripts

---

*Automation should reduce friction, not add complexity. Keep scripts lean and focused.*
