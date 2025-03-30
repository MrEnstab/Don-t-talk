# Don-t-talk
 <br>
<p align="center">
    <img align="center" src=https://github.com/user-attachments/assets/9dab3f42-33f8-4d8a-af86-59d08a184918>
    
</p>
<br>





Это небольшой проект-мессенджер на customtkinter работающий на ncat. Запустить можно на своем сервере(обязательно с белый ip, для доступа из любой точки мира!)

Тестировалась сборка на py2app, работает идеально

# Настройка
Для сервера:
```
sudo install nmap
```
```
ncat -klvp порт
```
В коде:
```
self.host = "тут белый ip сервера" 
self.port = "порт указанный в команде для сервера
```
Для сборки на MacOS лучше использовать py2app
