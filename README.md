# Ansible-Playbooks
This repository includes my Ansible Playbooks
<b>Quick Start:</b>
To run the Playbooks:

ansible-playbook playbook_name.yaml

#For the above step make sure that you have configured your ssh server to use keys instead of passwords. 
#See more from:https://www.techtimejourney.net/ssh-remote-desktop-and-ansible-tutorials-part-1-ssh-install-and-deployment/
_________________________

If you use passwords then the command is:
ansible-playbook playbook_name.yaml --ask-pass

Also, remember to tweak your ansible configuration and the host file. They can be found within the /etc/ansible pathway.
