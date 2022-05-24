# Playbooks

Playbooks to provision various machines I use on a daily basis:

- `macbook` - Macbook configured for development
- `server` - home server powered by Odroid H2+
- `vm` - Virtual Machine

## Provisioning

1. Install ansible
2. Create secrets file: `cp secrets.example.yml secrets.yml`
3. Customize secrets: `vim secrets.yml`
4. Provision selected server with a desired playbook: `ansible-playbook -i inventories/{machine} {machine}.yml`
