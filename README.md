# Homebrew Tap for token-audit

This is the official Homebrew tap for [token-audit](https://github.com/littlebearapps/token-audit), the token usage auditor for AI coding tools.

## Installation

```bash
brew tap littlebearapps/token-audit
brew install token-audit
```

Or in a single command:

```bash
brew install littlebearapps/token-audit/token-audit
```

## Usage

```bash
# Collect session data from Claude Code
token-audit collect --platform claude-code

# Generate a report
token-audit report

# Export for AI analysis
token-audit export ai-prompt

# Show version
token-audit --version
```

## What is token-audit?

token-audit analyzes token usage and MCP (Model Context Protocol) efficiency across AI coding sessions. It supports:

- **Claude Code** (Anthropic)
- **Codex CLI** (OpenAI)
- **Gemini CLI** (Google)

Key features:
- Session-by-session token usage analysis
- Cost estimation for API calls
- MCP tool usage patterns and efficiency metrics
- Context bloat detection ("smells")
- Export formats for further AI analysis

## Links

- [GitHub Repository](https://github.com/littlebearapps/token-audit)
- [PyPI Package](https://pypi.org/project/token-audit/)
- [Documentation](https://github.com/littlebearapps/token-audit#readme)

## Alternative Installation

You can also install via pip or pipx:

```bash
pip install token-audit
# or
pipx install token-audit
```
