# Ansible
## _Ansible Training_

In this task we created 4 yml file to run it by Ansible:

- vpc.yml - a new VPC with a single public subnet in AWS.
- key.yml - a new key in AWS keypair.
- instance.yml - a new instance (ubuntu) in your new VPC installed with Docker
- nginx.yml - an NGINX docker container on the instance using Ansible

to run each FILE.yml use:
```sh
ansible-playbook File.yml
```


