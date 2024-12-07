# Установка Apache, MySQL, PHP и WordPress с помощью Ansible

## Шаги по развертыванию

1. Установил Debian 12 на VirtualBox.
2. Создал структуру каталогов проекта Ansible.
3. Создал роли для установки Apache, MySQL, PHP и WordPress.
4. Создал файл инвентаря в `inventory.ini` с адресом хоста `192.168.56.12`.
5. Создал сценарий `playbooks.yml`, который использует созданные роли.
6. Запустил сценарий с помощью команды:
   ```bash
   ansible-playbook -i inventory/hosts playbooks/site.yml -kK | tee ansible_playbook.log
   ```

## Логи выполнения

Логи выполнения сценария можно найти в файле `ansible_playbook.log`.
