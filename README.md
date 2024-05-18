# ansible-copy-certs

## Инструкция

1. Установить ansible и python3 командой: ```sudo apt-get install ansible python3```
2. Заменить в файле hosts.ini HOST_ADDRESS и HOST_USER на реальные значения.
3. В файле playbook.yml заменить пути к файлам сертификатов на реальные.


После этих действий можно запустить скрипт командой:

```bash
ansible-playbook -i hosts.ini playbook.yml
```