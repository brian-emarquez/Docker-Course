FROM python:3.10.5-buster

COPY . usr/src/app

WORKDIR /usr/src/app

RUN pip install -r requirements.txt

# podemos instalar depencias en esta parte

ENTRYPOINT uvicorn --host 0.0.0.0 main:app --reload

#EXPOSE 80