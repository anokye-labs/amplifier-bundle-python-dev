# Amplifier Bundle Python Dev

Comprehensive Python development tools for [Amplifier](https://github.com/microsoft/amplifier) - the "Python Development Home" in the Amplifier ecosystem.

## Tech Stack
- YAML and Markdown configuration
- Part of the Amplifier framework ecosystem
- Python 3.11+ (for module components)

## Development
```bash
pip install -e ".[dev]"
python -m pytest
```

## Structure
This is an Amplifier bundle — a curated collection of agents, behaviors, context, and module configurations that extend Amplifier capabilities.

Key directories:
- `agents/` — Agent profiles and definitions
- `behaviors/` — Behavioral instructions
- `context/` — Context files and references
- `modules/` — Module configurations

## Conventions
- Follow existing YAML/Markdown patterns
- Keep bundle.md as the manifest
- Use descriptive names for agents and behaviors
