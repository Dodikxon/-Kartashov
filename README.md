# -Kartashov
Для того чтобы воспользоваться playbook`ом нужно:
1. Заменить файл /etc/ansible/hosts на виртуальной машине, на файл hosts, который загружен здесь.
2. Загрузить playbook в /etc/ansible/
3. Зайти в ту директорию в которой находиться playbook
4. Написать команду ansible-galaxy collection install ansible.posix
5. Дождаться конца загрузки
6. Ввести команду ansible-playbook -i hosts db.yml
