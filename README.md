DRF_Api Repo
LAB - Class 31 Project: some_API
Author: Myyela Isaac
Links and Resources - N/A
Setup - N/A
PORT - N/A
DATABASE_URL - N/A
How to use your library
pip install -r requirements.txt

How to initialize/run your application -
docker-compose up --build
docker-compose exec web python manage.py migrate
docker-compose exec web python manage.py createsuperuser
Tests How do you run tests? -
python manage.py tests