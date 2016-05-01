# Secure an Ubuntu server with Ansible

1. Add your public SSH Key in roles/secure/files/key.pub
2. Add your server IP/DNS in server.template
3. Launch `ansible-playbook -i server site.yml`