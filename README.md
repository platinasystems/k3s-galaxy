## Install galaxy roles
```
ansible-galaxy collection install git+https://github.com/k3s-io/k3s-ansible.git
```
```
ansible-galaxy collection install community.kubernetes
```

## Create cluster
```
ansible-playbook -e "@/tmp/k3s/vars.yml" /tmp/k3s/main.yml
``` 
