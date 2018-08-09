# Ansible role: systemd-cron
Enable systemd generator that translates cron jobs to systemd timers.

## Requirements
Only tested on Debian stable, for now.

Removes all other crons.

## Role Variables
None

## Dependencies
None.

## Example Playbook

```
- hosts: all
  roles:
    - { role: ho-ansible.systemd-cron }
```

## License
+ This ansible role is licensed [MIT](LICENSE).

## Author Information
+ This ansible role is by [Sean Ho](https://github.com/ho-ansible/)

