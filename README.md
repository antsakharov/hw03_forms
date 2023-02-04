# yatube_project

## Описание проекта: 

•	**Назначение:** 

Третья версия социальной сети для публикации личных дневников. 

•	**Реализованный функционал:** 

1. Настроен эмулятор отправки писем
2. Создано и подключено приложение core
3. Создано и подключено приложение about
4. Подключено приложение django.contrib.auth
5. Создано и подключено приложение users
6. Добавлена форма для публикации новых постов
7. Добавлена страница редактирования постов

•	**Цель выполнения проекта:**

Практика работы с фреймворком Django,БД,Админ-панелью

•	**Стек:**

Python 3.7, Django 2.2.19, SQLite, pytest

## Инструкция по развёртыванию проекта

•	**Клонируйте репозиторий:**

```csharp 
git clone git@github.com:antsakharov/yatube_project.git
```

•	**Установите и активируйте виртуальное окружение:**

**для Linux и MacOS**

```csharp 
python3 -m venv venv
```

**для Windows**

```csharp 
python -m venv venv
```

```csharp 
source venv/bin/activate
```

```csharp 
source venv/Scripts/activate
```

•	**Установите зависимости из файла requirements.txt:**

```csharp 
pip install -r requirements.txt
```
•	**Создайте и выполните миграции:**

```csharp 
python manage.py makemigrations
```

```csharp 
python manage.py migrate
```

