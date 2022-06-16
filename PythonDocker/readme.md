* Just Run Docker

```dif
sudo dockerd
```
## Docker

* Systemctl

```dif
systemctl start docker
```

* Construir imagen Docker

```dif
docker build -t simple_app .
```

* Construir Contenedor

```dif
docker run -it -p 8000:8000 -v $PWD:/usr/src/app simple_app
```

[stackoverflow](https://stackoverflow.com/questions/44678725/cannot-connect-to-the-docker-daemon-at-unix-var-run-docker-sock-is-the-docker)

## FastAPI

[FastAPI](https://fastapi.tiangolo.com/)

* Ejecutar FastAPI

```dif
uvicorn main:app --reload
```




