# Contributing to Main Project

## Code Standards

### JSON Files
- Use 2-space indentation
- Keep files well-organized with clear hierarchies
- Include comments for complex structures
- Validate against schema files

### File Naming
- Use lowercase with hyphens: `config-file.json`
- Be descriptive: `user-settings.json` not `us.json`

### Commits
- Use clear, descriptive commit messages
- Format: `type: description`
- Types: feat, fix, docs, chore, refactor

## Pull Request Process
1. Create a feature branch from main
2. Make your changes
3. Validate all JSON files
4. Submit PR with clear description
5. Wait for review

## Issues
- Report bugs with reproduction steps
- Suggest features with use cases
- Ask questions in discussions

## JSON Validation
Before committing, validate files:
```bash
# Using jq (if available)
jq empty config/settings.json

# Using Node.js
node -e "require('fs').readFileSync('config/settings.json', 'utf8') && console.log('Valid')"
```

## Questions?
Open an issue or start a discussion!
