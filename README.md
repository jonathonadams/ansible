# TODO

## Ansible Vault 
Encrypt / decrypt : `ansible-vault encrypt/decrypt somefile`

Initial install `curl -sSf https://github.com/jonathonadams/ansible/install | sh`

Local execution `ansible-playbook local.yml --ask-become-pass --ask-vault-pass -t never`

Remote execution `ansible-pull git@github.com:jonathonadams/ansible.git --ask-become-pass --ask-vault-pass -t never`