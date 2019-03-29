# local-fedora-setup

## prereqs

```shell
$ sudo visudo
$ sudo dnf install ansible
```

## run

```shell
$ ansible-playbook -t <tag> playbooks/install.yml
```
or
```shell
$ ansible -vv --playbook-dir playbooks/roles/ -m include_role -a name=<role_name> localhost
```
