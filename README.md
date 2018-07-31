# learninglog
Python Django project - Python Crash Course

# Create a virtual environment
virtualenv ll_env

# Activate virtual environment
source ll_env/bin/activate

# Stop virtual environment
deactivate

# Install Django
pip install Django

# Create a project
django-admin.py startproject learning_log .

# Create the database
python manage.py migrate

python manage.py makemigrations learning_logs
python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
