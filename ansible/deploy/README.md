- [About](#about)
- [Variables](#variables)

# About

This GitLab CI template can be included for Ansible deployments

# Variables

| Variable                     | Description                                       | Default       | Optional/Required |
|------------------------------|---------------------------------------------------|---------------|-------------------|
| ANSIBLE_INVENTORY:           | Name of the inventory file                        | inventory.ini | Required          |
| ANSIBLE_PLAYBOOK_DIRECTORY:  | Directory for the playbook.yml file               | ansible       | Required          |
| ANSIBLE_PLAYBOOK:            | Playbook name                                     | playbook.yml  | Required          |
| ANSIBLE_VAULT_PASSWORD:      | Ansible vault password                            |               | Optional          |
| ANSIBLE_EXTRA_VARS:          | Extra variables. Pass as VAR=VALUE without quotes |               | Optional          |
| ANSIBLE_TAGS:                | Tags to be used when deploying the playbook       |               | Optional          |