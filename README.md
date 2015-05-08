# ansible-chroot-sftp

Just an Ansible playbook using franklinkim's https://github.com/weareinteractive/ansible-sftp to create sftp jails

1. ansible-galaxy install -r requirements.txt
2. echo "IP ADDRESSES for your Ubuntu server(s)" >> inventory
3. ansible-playbook -i inventory ansible-chroot-sftp.yml