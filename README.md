# Hyonchoi's Claude Code Plugins

A marketplace for Claude Code plugins by Hyonyoung Choi.

## Plugins

| Plugin | Description | Skills |
|--------|-------------|--------|
| [git-atomic-commits](https://github.com/hyonchoi/git-atomic-commits) | Atomic git commits and project initialization | `git-atomic-commits`, `git-init` |

## Installing the Marketplace

```bash
claude plugin marketplace add hyonchoi/claude-plugins-marketplace
```

## Installing a Plugin

```bash
claude plugin install git-atomic-commits@hyonchoi-plugins
```

## Developing

Marketplace definition lives in `.claude-plugin/marketplace.json`. Validate it before publishing:

```bash
claude plugin validate .
```
