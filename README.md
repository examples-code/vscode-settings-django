# vscode-settings-django
Настройки рабочей области VSCode для Django проекта

### 1. Создать виртуальное окружение:

```
python3.10 -m venv django_env && \
source django_env/bin/activate && \
pip install --upgrade pip
```

### 2. Установит зависимости

```
pip install -r ./requirements.txt
```

### 3. Создание проекта, точка - в текущей директории
```
django-admin startproject project .
```


### 4. Запустить сервер разработки:

```
python manage.py migrate
python manage.py runserver
python manage.py createsuperuser
```
