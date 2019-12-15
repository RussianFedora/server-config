# server-config

Ansible configuration for the test server of Russian Fedora community.

# Execution

`site.yaml` requires root access to the server

```
$  ansible-playbook -i inventory site.yaml

```

# Roles

## ssh-setup

Enable SSH server, add users, configure MOTD.

# Hosts

## Build server

Build server variables are set in `inventory/host_vars/build-server.yaml`.
