# Claude Code Templates

> Claude Code slash command templates for Modsynth

Part of the [Modsynth](https://github.com/modsynth) ecosystem.

## Features

- Slash commands for common tasks
- Module integration templates
- Quick setup commands

## Installation

Copy the `.claude/commands/` directory to your project:

```bash
cp -r .claude your-project/
```

## Available Commands

- `/add-module` - Add a Modsynth module to your project
- `/create-api` - Create a new API endpoint
- `/setup-frontend` - Setup React frontend with modules
- `/add-monitoring` - Add Prometheus monitoring

## Usage

In Claude Code, type `/` to see available commands.

## Creating Custom Commands

Add new `.md` files to `.claude/commands/`:

```markdown
# Command Title

Command description and instructions.
```

## Version

Current version: `v0.1.0`

## License

MIT
