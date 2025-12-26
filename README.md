# Лабораторная работа: Основы Ansible в DevOps
Ягудин Ильдар ПИ-431Б
##Задание 1: Базовое подключение

1. Установили Ansible

2. Сгенерировали SSH ключевую пару
![alt text](image1.png)

3. Создали инвентарный файл inventory.ini


4. Проверили подключение командой ansible-inventory --list
![alt text](image2.png)

5. Выполнили ping к управляемому хосту
![alt text](image3.png)

---
##Задание 2: Базовые ad-hoc команды

1. Получили информацию о ядрах CPU управляемого хоста:
![alt text](image4.png)

2. Проверили свободное место на диске:
![alt text](image5.png)

3. Получили список всех пользователей:
![alt text](image6.png)
---
##Задание 3: Работа с файлами
1. Создали новый playbook task3_files.yml

2. Запустили playbook:
![alt text](image7.png)