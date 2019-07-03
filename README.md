# oh-my-zsh

This role handles installing oh-my-zsh and setting the Ansible user's shell to
zsh.

## Requirements

The hosts you are targeting should have the following packages:

- git >= 1.7.1
- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.oh_my_zsh
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)
