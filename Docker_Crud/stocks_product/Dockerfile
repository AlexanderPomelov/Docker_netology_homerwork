FROM python:3.9

WORKDIR 3.2_Crud

COPY . .

RUN pip install -r requirements.txt 
RUN python3 manage.py migrate



CMD [ "python3", "manage.py", "runserver"]