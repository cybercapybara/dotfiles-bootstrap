# dotfiles-bootstrap

> Rebuild my entire dev environment on a fresh machine with one command.

**Status:** 🚧 In development

## Overview

A reproducible personal dev environment: dotfiles plus an idempotent bootstrap via Ansible/Nix.

## Features

- Version-controlled dotfiles (shell, git, editor) with a clear layout
- Idempotent `bootstrap.sh` that installs tools and symlinks config
- Ansible playbook (or Nix flake) for reproducible package installs
- Per-host overrides and secrets kept out of git
- Works on a fresh Linux box end to end

## Stack

Shell + Ansible (or Nix flake), GNU stow-style symlinking.

## Usage

```bash
git clone https://github.com/moveeeax/dotfiles-bootstrap ~/.dotfiles
cd ~/.dotfiles && ./bootstrap.sh
```

## License

MIT
