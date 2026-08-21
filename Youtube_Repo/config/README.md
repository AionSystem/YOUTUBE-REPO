# Configuration Files

## Purpose

This folder contains configuration files for tools, workflows, and automation.

## Configuration Types

### Tool Configurations
- OBS Studio profiles
- CapCut settings
- Editor preferences

### Workflow Configurations
- Pipeline settings
- Naming conventions
- Template references

### Environment Files
- API keys (template only, never commit real keys)
- Path configurations
- Environment variables

## Standards

### File Format
- Use `.yaml` or `.json` for structured configs
- Use `.env.example` for environment templates
- Include comments explaining non-obvious settings

### Version Control
- Commit configuration templates
- **Never commit real credentials or API keys**
- Use `.gitignore` for sensitive files

### Documentation
Each config file should include:
- Purpose description
- Required fields
- Default values
- How to customize

## Example Structure
```
config/
├── obs/
│   └── profile_settings.json
├── capcut/
│   └── export_presets.yaml
├── workflow/
│   ├── naming_convention.yaml
│   └── pipeline_config.json
├── .env.example
└── README.md
```

## Sensitive Data

Use `.env.example` as a template:
```bash
# Copy to .env and fill in real values
# NEVER commit .env to git
API_KEY=your_key_here
SECRET_TOKEN=your_token_here
```

Add to `.gitignore`:
```
.env
*.key
*.secret
```

---

*Configuration should be reproducible across machines while protecting sensitive data.*
