# Ansible Role for RedHat OpenSCAP Hardening
**Author/Maintainer:** Josh Murphy

## Overview

This Ansible role automates hardening of RedHat Distros to the CIS Server Level 2 Benchmark using OpenSCAP:

## Supported Platforms and Derivatives
```yaml
# RedHat
Rocky Linux - 9-10
CentOS Stream - 9-10
Other RHEL - 9-10
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