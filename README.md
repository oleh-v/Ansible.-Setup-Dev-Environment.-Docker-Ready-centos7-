# [Ansible](https://www.ansible.com). Setup Dev-Environment. Docker Ready (centos7)

This Playbook install [Docker CE](https://docs.docker.com/install/), [Docker-Compose](https://docs.docker.com/compose/install/), Samba (/host will be available), dissable SeLinux, Configure Firewall, add user "dev:dev", install common tools, etc on CentOS server. 


## Requirements
* SSH root access to the target servers. 

How to do that: Copy your public key to the target server with command below:
```
ssh-copy-id root_user@target.server.com
```

## Usage
* In ./ansible.cfg - check path to your private key and username 
* Run Playbook:
```
ansible-playbook run.yml
```


