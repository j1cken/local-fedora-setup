# local-fedora-setup

## prereqs

```shell
$ sudo visudo
$ sudo dnf install ansible
```

## run

```shell
$ ansible-playbook -l <tag> playbooks/install.yml
```
