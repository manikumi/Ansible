# copy key from source server to target server
ssh-copy-id target_server_private_IP

# check the connection details of ansible 
ansible all -m ping

# uptime of ansible
ansible all -m command -a uptime

# check ansible playbook
ansibe-playbook Playbook_yml_file --check

# limit ansible playbook to execute on server
ansibe-playbook Playbook_yml_file --limit private_ip_of_server

# default host of ansible
/etc/ansible/hosts
