# Ansible Role: Node.js

Installs Node.js and npm

## Supported platforms

```
CentOS 6 & 7
Ubuntu 14.04
```

## Requirements

None

## Role Variables

None

## Dependencies

```
pcextreme.repo-epel
```

## Example Playbook

```
- hosts: servers
  roles:
    - { role: pcextreme.nodejs }
```

## License

MIT / BSD

## Author Information

Created by [Attila van der Velde](https://github.com/vdvm)
