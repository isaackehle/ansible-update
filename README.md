# Ansible Role - sysupdate

This role will handle system updates

## Requirements

None

## Role Variables

NA

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
         - pgkehle.sysupdate

## Hacking

```
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yaml
...
```

## License

BSD

## Author Information

Paul Kehle  
@pgkehle (twitter, gmail, github, linkedin)
