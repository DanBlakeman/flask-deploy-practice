FROM python:2.7

ADD



RUN pip install -r ./flask-deploy-practice/requirements.txt

EXPOSE 8000

WORKDIR ./flask-deploy-practice

CMD gunicorn -c gunicorn.conf.py app:app