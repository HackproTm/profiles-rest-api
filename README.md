# Profiles REST API

Profiles REST API course code.

vagrant up => Start VM
vagrant ssh => Connect to VM
cd /vagrant
python -m venv ~/env
source ~/env/bin/activate
pip install -r requirements.txt

python manage.py makemigrations profiles_api
python manage.py migrate

python manage.py createsuperuser

python manage.py runserver 0.0.0.0:8000
