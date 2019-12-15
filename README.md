# server-config

Ansible configuration for the test server of Russian Fedora community.

# Execution

`site.yaml` requires root access to the server

```
$  ansible-playbook -i hosts site.yaml

```

# Roles

## ssh-setup

Enable SSH server, add users, configure MOTD.
