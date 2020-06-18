# microblog
Web application with use Python, Flask, SQLite
# Запуск и настройка первоначальных настроек Python и других утилит через командную строку Windows (cmd)

Переход к каталогу
```
cd /D D:\py\microblog
```
Активация виртуальной среды
```
venv\Scripts\activate
```
### Установка Flask
```
pip install flask

(venv) $ set FLASK_APP=microblog.py
```
Проверка установки Flask
```
(venv) $ py
>>> import flask
```
        
Расширения для Flask	
```
(venv) $ pip install flask-wtf
(venv) $ pip install flask-sqlalchemy
(venv) $ pip install flask-migrate
```          
### Запуск сайта
```
(venv) $ flask run
```
