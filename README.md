### Как запустить проект:

Клонируйте репозиторий:

```
git clone git@github.com:31-Cronos-33/api_final_yatube.git
```

Создайте и активируйте виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/Scripts/activate
```

Установите зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Перейдите в директорию yatube_api и выполните миграции:

```
cd yatube_api
```

```
python manage.py migrate
```

Запустите проект:

```
python manage.py runserver
```