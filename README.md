# README.md
# Ansible Role: freee.awscli

An Ansible role that installs awscli on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yaml
awscli_install_dir: /usr/local/aws
awscli_bin_location: /usr/local/bin/aws
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: ec2-server
  roles:
    - role: freee.awscli
      awscli_install_dir: /opt/aws
```

## License

Apache License 2.0
