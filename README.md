# playbooks

Playbooks for setting up rpis.

## Usage

```shell
# set up ssh-keys
ansible-playbook ssh.yml -k --ask-vault-pass

# set up a new machine
ansible-playbook setup.yml -K --ask-vault-pass

# set up docker
ansible-playbook docker.yml -K --ask-vault-pass

# set up sense-hat
ansible-playbook hat.yml -K --ask-vault-pass

# install required packages for running haskell binaries
ansible-playbook hre.yml -K --ask-vault-pass

# reboot a machine
ansible-playbook reboot.yml -K --ask-vault-pass
```

