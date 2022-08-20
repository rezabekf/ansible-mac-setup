# Ansible macOS Setup
Ansible script for setting up a Mac for development.

## Prerequisites

- Complete the macOS setup
- Install command-line-tools (`xcode-select --install`)
- Login to AppStore app.

## Installation

1. Install [Homebrew](https://brew.sh).
2. Install Ansible (`brew install ansible`)
3. Copy `default.config.yml` to `config.yml` and edit the configuration to your likings
   (`cp default.config.yml config.yml`).
4. Run `ansible-playbook main.yml`. Enter your account password when prompted.

## Acknowledgements

This playbook is heavily inspired by
[Jeff Geerling's mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook).
