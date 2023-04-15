# authentik-ansible
Ansible playbook for setting up a authentik VM


# Setup prerequisites

## Install Python/pip

## Install Ansible
```
pip install ansible
```

## Copy/Edit .env example
In roles/docker-compose/templates is a .env.example you need to copy
```
cp roles/docker-compose/templates/.env{.example,}
```
Now modify and replace what you will need for your homelab in that example.

## Copy/Edit inventory example
In the root is a inventory.example you need to copy
```
cp inventory{.example,}
```
Now modify and replace what you will need for your homelab in that example.

# Run

## Apply playbook with the following:
```
ansible-playbook app.yml --ask-become-pass
```
