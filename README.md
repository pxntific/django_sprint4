запуск из django_sprint4:

python -m venv venv

source venv/Scripts/activate

python -m pip install --upgrade pip

pip install -r requirements.txt

cd ./blogicum

python manage.py migrate

python manage.py loaddata db.json

python manage.py runserver

вставить http://127.0.0.1:8000/ в браузер

CTRL+C чтобы остановить сервер
