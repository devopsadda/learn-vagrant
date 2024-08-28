# Let's Learn Vagrant
## Ansible Learning Materials

## Learning notes - concepts
### Install Vagrant from the official website.
https://developer.hashicorp.com/vagrant/install?product_intent=vagrant

### let's create a centos7 vagrant box

```shell
vagrant --version
cd centos7
vagrant init
vagrant up
vagrant box list
vagrant ssh
```

### Vagrant Commands

![alt text](image.png)

### Vargant Box Commands
```shell
vagrant box add ubuntu/focal64
vagrant box list
vagrant box outdated
vagrant box update ubuntu/focal64
vagrant box repackage ubuntu/focal64 --name my-new-box
vagrant box prune
vagrant box remove ubuntu/focal64
```

## Hands-On Labs
## POC Solutions/Projects
## Interview Q/A


