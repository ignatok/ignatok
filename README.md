
source venv/bin/activate 

pip install -r requirements.txt
Run the web application locally,
Run Celery
celery -A bankingsystem worker -l info
celery -A bankingsystem beat -l info
