# GitHub Workflows

## Purpose

This folder contains GitHub Actions workflows for automating repository tasks.

## Potential Workflows

### CI/CD
- Lint check on pull requests
- Automated testing for scripts
- Build validation

### Production Automation
- Auto-organize new episode folders
- Validate file naming conventions
- Check for required metadata files

### Documentation
- Auto-generate changelog
- Deploy documentation site (if applicable)
- Link checker

### Quality Assurance
- Run compliance checks
- Validate configuration files
- Check for sensitive data commits

## Workflow Standards

### File Naming
```
[action]-[target].yml
Example: lint-scripts.yml
Example: validate-naming.yml
```

### Structure
Each workflow should include:
- Clear name
- Trigger conditions
- Job descriptions
- Step documentation

### Best Practices
- Keep workflows focused (one job per workflow)
- Use reusable workflows where possible
- Document trigger conditions clearly
- Test workflows before deploying to production

## Example Workflow

```yaml
name: Validate Episode Structure

on:
  push:
    paths:
      - 'series/AION_Forge_and_Fracture/episodes/**'

jobs:
  validate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Check folder structure
        run: ./scripts/validate_episode.sh
```

## Security Notes

- Never expose API keys or secrets in workflows
- Use GitHub Secrets for sensitive values
- Limit workflow permissions to minimum required
- Review third-party actions before use

---

*Automation should reduce manual work without adding fragility to the production process.*
