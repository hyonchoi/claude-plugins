# Hyonchoi's Codex Plugins

A marketplace for Codex plugins by Hyonyoung Choi.

## Plugins

| Plugin | Description | Skills |
|--------|-------------|--------|
| [git-atomic-commits](https://github.com/hyonchoi/git-atomic-commits) | Atomic git commits and project initialization | `git-atomic-commits`, `git-init` |

## Installing the Marketplace

```bash
codex plugin marketplace add hyonchoi/codex-plugins
```

## Installing a Plugin

```bash
codex plugin install git-atomic-commits@hyonchoi-plugins
```

## Developing

Marketplace definition lives in `marketplace.json`. Validate it before publishing:

```bash
codex plugin validate .
```
