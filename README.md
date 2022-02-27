# -Kartashov
Для того чтобы воспользоваться playbook`ом нужно:
1. Дописать в файле /etc/ansible/hosts (в конце) :

Project_1 ansible_user=root ansible_host=192.168.201.10 ansible_ssh_pass=toortoor

Project_2 ansible_user=root ansible_host=192.168.201.20 ansible_ssh_pass=toortoor

Project_3 ansible_user=root ansible_host=192.168.201.30 ansible_ssh_pass=toortoor

2. Клонировать playbook в /etc/ansible/
3. Зайти в ту директорию в которой находиться playbook
4. Написать команду ansible-galaxy collection install ansible.posix
5. Дождаться конца загрузки
6. Ввести команду ansible-playbook -i hosts playbook.yml
