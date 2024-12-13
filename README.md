# Ansible Runbook: reboot_system

[![Build](https://github.com/dcjulian29/ansible-runbook-reboot_system/actions/workflows/build.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-reboot_system/actions/workflows/build.yml) [![GitHub Release](https://img.shields.io/github/v/release/dcjulian29/ansible-runbook-reboot_system)](https://github.com/dcjulian29/ansible-runbook-reboot_system/releases) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-runbook-reboot_system.svg)](https://github.com/dcjulian29/ansible-runbook-reboot_system/issues)

This an Ansible runbook that will update the operating system and reboot if needed.

## Requirements

- Internet Connection

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
collections:
- name: dcjulian29.reboot_system
  type: git
  source: https://github.com/dcjulian29/ansible-runbook-reboot_system.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy collection install -r requirements.yml
```

To excute the runbook:

```shell
ansible-playbook dcjulian29.reboot_system.runbook.yml
```
