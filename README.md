# install-nginx-ansible
Ansible playbook to install nginx on servers

### Prerequisites:

Python should be installed on remote servers.

### Running instructions:

Update hosts file with IP Address / host name of server and provide user name and pem file path.

To run this playbook, use below command:

```
$ ansible-playbook -i hosts site.yml 
```
