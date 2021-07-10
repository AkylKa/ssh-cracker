# Введение
Вступление

Сканер nmap и инструмент hydra, сначала используйте nmap, чтобы определить, открыт ли порт 22,eсли он открыт используйте hydra для подбора пароля.
# Установка
Arch linux: ```sudo pacman -S nmap hydra```


Ubuntu: ```sudo apt install nmap hydra```
# Запуск
Запустите программу

./hydra.sh -p ./password.txt -f ./iplist.txt # Подбор пароля в IP-листе

./hydra.sh -p ./password.txt -l 192.168.9.0/24 # Подбор пароля в сегменте сети
# Сборник паролей 
https://github.com/danielmiessler/SecLists/tree/master/Passwords
