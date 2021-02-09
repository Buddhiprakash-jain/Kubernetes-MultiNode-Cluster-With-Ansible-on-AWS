# Kubernetes-MultiNode-Cluster-With-Ansible-on-AWS

## WHAT TO DO FOR RUNNING THE SCRIPT->
1. Change in ansible conf(/etc/ansible/ansible.cfg) file in your vm "inventory='your inventory folder'"
2. Change "roles-path='path of your role'" in ansible conf file that is /etc/ansible/ansible.cfg
3. Change "remote_user='ec2-user'" in ansible conf file that is /etc/ansible/ansible.cfg
4. Change "ansible_private_key='path of your key" in ansible conf file that is /etc/ansible/ansible.cfg
5. Change permission of your private key by run cmd in bash shell "chmod 400 'key name'"
6. For dyanamic inventory run following commands in bash shell
   - export AWS_ACCESS_KEY_ID='access-key-id'
   - export AWS_SECRET_ACCESS_KEY='secret-access-key'
   - export AWS_REGION='region name'
7. Make sure your master instances name is "master"
8. Make sure your worker instances name is "worker"
