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

## Credits

- [Attila van der Velde](https://github.com/vdvm)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
