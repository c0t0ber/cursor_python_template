# Python Project Template for Cursor

Welcome to this Python project template adapted for use with the Cursor editor. This template provides a structured starting point for your Python applications with modern tooling and best practices built in.

## 🚀 Getting Started

### Prerequisites

This template requires:

- [UV](https://github.com/astral-sh/uv) for dependency management
- [just](https://github.com/casey/just) command runner
- https://marketplace.visualstudio.com/items?itemName=ms-python.python

### Quick Setup

1. Clone this repository
2. Rename the following components to match your project name:
   - The `you_app_srcs` module
   - Project name in `pyproject.toml`
   - `__name__` in `__init__.py`
3. Install dependencies:
   ```bash
   just init-venv
   just update-deps
   just install-deps
   ```
4. Start developing!

## 📁 Template Structure

```
.
├── pyproject.toml         # Project configuration and dependencies
├── justfile               # Command runner tasks
├── you_app_srcs/          # Main source directory (rename this!)
│   ├── __init__.py        # Package initialization
│   └── ...                # Your modules go here
└── CHANGELOG.md           # Documentation of changes
```

## 🛠️ Development Commands

This template uses `just` for command running:

- `just fmt` - Format code
- `just lint` - Lint code
- `just update-deps` - Update dependencies
- `just install-deps` - Install dependencies

## 🔄 Customization

Feel free to ask the agent to rename files to match your application name. For example:

> "Please rename the you_app_srcs directory and references to my-awesome-app"

## 📝 Development Guidelines

This template encourages:

- Composition over inheritance
- Type hints for everything (checked by mypy)
- Comprehensive documentation
- Proper logging practices
- Modern Python features
