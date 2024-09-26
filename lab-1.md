1. Cкачала virtual ubuntu на windows
2. Oбновила wsl (windows linux subsystem) => чтобы была более свежая версия
3. Прописала команду `sudo apt-get update` (чтобы внутри убунту были наиболее свежие библиотеки, старый апт ссылался на старые файлы кот больше не существуют)
   apt - система которая инсталлирует программы
5. Cкачала gedit  `sudo apt install gedit`

Итак, можно приступать к лабараторной работе


6. Создала новый файл с именем `script.bash`

```bash
touch script.bash
```
7.Открыла созданный файл `script.bash` для редактирования. 
```bash
gedit script.bash
```
8. Вписала следующий скрипт

```bash
#!/bin/bash

echo "Welcome to ITMO University"
```
![screenshot_1](https://github.com/user-attachments/assets/24605719-9d59-418b-8c7c-7178859f3ffc)



9. Сохранила файл. Закрыла текстовый редактор `gedit`. Запустила bash-скрипт, выполнив в терминале

```bash
bash script.bash
```
10. В терминале отобразилась строка `Welcome to ITMO University`.
![image](https://github.com/user-attachments/assets/ab6faa3f-3972-49b1-a2de-097c736040e7)


12. Чтобы модифицировать файл `script.bash` и выполнить задание, я вписала следующий скрипт
    
```bash
#!/bin/bash
echo "Welcome, $@"
```
![image](https://github.com/user-attachments/assets/b943b5e2-7b31-492b-a628-9d4fc3cac0c4)

12. При вводе в командной строке `bash script.bash Anastasia Lebedeva` отобразилась строка `Welcome, Anastasia Lebedeva`

![image](https://github.com/user-attachments/assets/1df220d0-215f-4a54-b333-3a1e0b988fe9)
