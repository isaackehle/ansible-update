# Ansible Role - update

Handle system updates

Available on Ansible Galaxy: [isaackehle.update](https://galaxy.ansible.com/isaackehle/update)

## Requirements

None

## Role Variables

NA

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - isaackehle.update
```

## Hacking

There is an included Vagrant setup for hacking on this module, but IP needs to be set.

```bash
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yml
...
vagrant destroy
vagrant up
ansible-playbook test.yml -vvvv
...
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))
