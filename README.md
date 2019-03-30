# ansible-sonarr

This ansible role installs, configures, and runs sonarr.

## Requirements

This role was tested on a raspberry pi running raspbian (stretch).

## Role Variables

These variables are largely straight out of the sonarr config file. See [config.xml](templates/config.xml) and the [defaults](defaults/main.yml).

## Example Playbook

```yml
    - hosts: pi
      roles:
        - role: mpataki.sonarr
          tags: sonarr
```
