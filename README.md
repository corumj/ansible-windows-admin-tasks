# Ansible Windows Admin Tasks

Playbooks that show generic Windows administration tasks with Ansible

## Setup
To use the demo_setup.yml you'll need to have ansible-tower-cli installed `pip install ansible-tower-cli`

Then configure the cli with this, making sure to udpate the info to your environment:

```
$ tower-cli config host tower.example.com
$ tower-cli config username leeroyjenkins
$ tower-cli config password myPassw0rd
$ tower-cli config verify_ssl false
```

Then just run `ansible-playbook demo_setup.yml`