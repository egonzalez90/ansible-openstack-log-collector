# ansible-openstack-log-collector
Central log collector for OpenStack services

Currently not finished yet, but works on CentOS 7 and OpenStack liberty.
Planed to allow support for Ubuntu.

How to use it:

Clone the repo in your system.

Edit /etc/ansible/hosts with the following

[LOG_COLLECTOR]
#Node where logs are going to be collected
192.168.1.10
[OPENSTACK]
#Openstack nodes
192.168.1.101

Start installation with

ansible-playbook site.yml


Report any issues, to fix it



