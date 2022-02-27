# -Kartashov
Для того чтобы воспользоваться playbook`ом нужно:
1. Дописать в файле /etc/ansible/hosts в конце :
2. Project_1 ansible_user=root ansible_host=192.168.201.10 ansible_ssh_pass=toortoor
3. Project_2 ansible_user=root ansible_host=192.168.201.20 ansible_ssh_pass=toortoor
4. Project_3 ansible_user=root ansible_host=192.168.201.30 ansible_ssh_pass=toortoor
5. Загрузить playbook в /etc/ansible/
6. Зайти в ту директорию в которой находиться playbook
7. Написать команду ansible-galaxy collection install ansible.posix
8. Дождаться конца загрузки
9. Ввести команду ansible-playbook -i hosts db.yml
