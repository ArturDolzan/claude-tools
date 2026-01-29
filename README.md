# Claude Tools

Git commit standards plugin for Claude Code.

## Features

**`/git-standards:github-commit`** - Enforces git commit best practices.

## Installation

```bash
git clone https://github.com/arturdolzan/claude-tools ~/.claude/plugins/git-standards
```

Or for development:

```bash
git clone https://github.com/arturdolzan/claude-tools ~/dev/claude-tools
ln -s ~/dev/claude-tools ~/.claude/plugins/git-standards
```

## Usage

In any git repository:

```bash
/git-standards:github-commit
```

Or let Claude invoke it naturally:

```
commit these changes
```

## Testing Locally

```bash
claude --plugin-dir ./claude-tools
```
