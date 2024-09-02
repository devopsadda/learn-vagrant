### Setup SSH passwordless Authentication
```shell
ssh-keygen
ssh-copy-id vagrant@192.168.10.12
ssh-copy-id vagrant@192.168.10.13
```

### Test below Ansible Command on the Ansible Environment
```shell
ansible -i inventory all -m ping
```