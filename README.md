ui-auto-ansible
===============

 ui automation ansible script
 1. get Linux box
 2. install Ansible from page: http://docs.ansible.com/intro_installation.html
 3. git clone this repository: amiedingv/ui-auto-ansible
 4. use ansible_hosts.example to set up your target list(Your IT department should give you username and password or private or public key to cloud computers)
 5. testing connections using: `ansible all -m ping -i ansible_hosts -l rails_server` or `ansible rails_server -m ping -i ansible_hosts`
 6. deploy your playbooks: `ansible-playbook -i ansible_hosts site.yml `
 
