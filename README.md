# BasicAnsible

Ansible is helpful in creating the group of machines, define how to configure them, what action to be taken on them. All these configurations and actions can be triggered from a central location which can be your local system (named controller machine). Ansible uses SSH to connect to remote hosts and do the setup, no software needed to be installed beforehand on a remote host. It's simple, agentless, powerful and flexible. It uses YAML in form of ansible playbook. Playbook is a file where automation is defined through tasks. A task is a single step to be performed like installing a package.

Install ansible using link: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

Command to run : 

ansible-playbook playbook.yml
