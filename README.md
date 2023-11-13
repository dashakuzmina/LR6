# Лабораторная работа №6. Система контроля версий
## Цель лабораторной работы:
изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
## Ход работы:
### 1. Клонирование репозитория, изменение имени пользователя и email.

![рисунок 1](./images/image1.png)

![рисунок 2](./images/image2.png)

### 2. Добавление файла через интерфейс GitHub и загрузка изменений.

![рисунок 3](./images/image3.png)

### 3. Получение истории операций для каждой из веток.

![рисунок 4](./images/image4.png)

![рисунок 5](./images/image5.png)

### 4. Слияние в ветку master.

![рисунок 6](./images/image6.png)

### 5. Удаление ветки.
 
![рисунок 7](./images/image7.png)

### 6. Добавление файла и коммита.

![рисунок 8](./images/image8.png)

### 7. Откат коммита.

![рисунок 9](./images/image9.png)

### 8. Создание ветки для отчета.

![рисунок 10](./images/image10.png)

### 9. Добавление скриншотов.

![рисунок 12](./images/image12.png)

### 10. Загрузка директории в ветку для отчета.

![рисунок 13](./images/image13.png)

### 11. Полученная история операций.

![рисунок 14](./images/image14.png)

## Лог команд:
```
git config user.name "4216 Кузьмина Д.К"
git config user.email "dashagolynga@icloud.com"
git clone
git pull
git checkout master
git log
git checkout branch1
git log
git checkout master
git merge branch1
git add mergefile.txt
git commit -m "конфликт разрешен"
git push origin
git branch -d branch1
git add .
touch file1.txt
git add file1.txt
git commit -m "добавила file1"
git reset --hard HEAD
git log
git branch report
git checkout report
git push origin
git add .
git commit -m "Создана папка images"
git add .
git commit -m "Добавлены еще скриншоты"
git push origin report
git add .
git commit -m "Добавлен скриншот 13"
git push origin report
git log --pretty=format:"%h - %an, %ar : %s"
```
## Вывод:
В ходе лабораторной работы мы изучили базовые возможности системы управления версиями, получили опыт работы с Git Api и опыт работы с локальным и удаленным репозиториями.
