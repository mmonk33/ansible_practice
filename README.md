# Ansible-playbook

Добалвены hosts в inventory-файл hosts.txt

```bash
ansible-playbook -i hosts.txt mysql_install.yml
ansible-playbook -i hosts.txt docker_run_install.yml
```
## tail -2 /etc/passwd 
```
mmonk33:x:1000:1001::/home/mmonk33:/bin/bash
user1:x:1001:1002::/home/user1:/bin/bash
mmonk33@test:~$ 
```