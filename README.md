Ansible roles to install
 * iptables to block everything but https, http, ssh
 * asterisk with blacklist for Swiss call centers

on Debian Buster

```bash
ansible-playbook -i ./hosts webserver1.yml --vault-password-file .vault_pass
```

