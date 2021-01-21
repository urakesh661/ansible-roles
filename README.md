# ansible-roles

Command for deploying ansible playbook:

ansible-playbook -i /home/rocky2311/Desktop/Ansible/hosts httpdrole.yml 

On execution,all the tasks will be performed on all the below available hosts in centos group and handler will be triggered for all hosts as well.

Content of hosts file:

[centos]

host1 ansible_user=root
host2 ansible_user=root
host3 ansible_user=root
host4 ansible_user=root
host5 ansible_user=root
host6 ansible_user=root
