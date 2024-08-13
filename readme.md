Установка wg-easy и 3x WireGuard на VDS

```bash
# Проверка доступности хостов
ansible vds -m ping -i inventory.ini

# Запуск плейбука
ansible-playbook -i inventory.ini --become playbook.yaml
```

Минимальная версия ансибла
```plantuml
$ pip list | grep ansible
ansible                   8.7.0
ansible-core              2.15.11
```