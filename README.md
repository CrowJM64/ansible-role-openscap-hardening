# Ansible Role for RedHat OpenSCAP Hardening
**Author/Maintainer:** Josh Murphy

## Overview

This Ansible role automates hardening of RedHat Distros using OpenSCAP:

## Supported Platforms and Derivatives
```yaml
# RedHat
EL - All Versions
Fedora - All Versions
Rocky - All Versions
AlmaLinux - All Versions
```

## Example Playbook

```yaml
- hosts: all
  become: yes

  roles:
    - role: openscap_hardening
```

### From Ansible Galaxy

```bash
ansible-galaxy install crowjm64.openscap_hardening
```

This role was created and is maintained by **[CrowJM64](https://github.com/CrowJM64)**.