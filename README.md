# ansible_dellos10_config_backup
Ansible playbook to store configuration backups for Dell OS10 devices

# how to play
- clone this repo to your ansible control host
- edit inventory file:
  - ip addresses
  - login credentials
  - path of directory where configs are stored
- run the play with ansible-playbook play.yml
- if no reachability test: ansible all -m ping

# requirements
- python3 installed
- ansible installed
