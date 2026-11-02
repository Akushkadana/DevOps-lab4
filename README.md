# Лабораторная работа 4. Ansible

Playbook `lab4.yml` настраивает Ubuntu-сервер:

1. устанавливает пакеты htop и tree;
2. создаёт пользователя devuser с оболочкой /bin/bash;
3. создаёт каталог /opt/lab4 (владелец devuser, права 0755);
4. создаёт файл /opt/lab1/info.txt с ФИО;
5. запускает службу cron и включает её в автозагрузку.

## Запуск

    ansible-playbook -i lab.ini lab4.yml -K

Маликова Айдана
