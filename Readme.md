# Curso fastapi python

## iniciar con el proyecto desde cero o arrancarlo
1. Generar entorno virtual "es necesario tener instalado de manera global venv".
```shell
$ python -m venv <name_enviroment>
```

2. Activar entorno.
```shell
# windows
$ <nameEnv>/Script/activate
# linux
$ source <nameEnv>/bin/activate
```

3. instalar modulos.
```shell
# proyecto desde cero
$ pip install fastapi
# arrancar este proyecto
$ pip install -r requirements.txt
# instalar un nuevo modulo
$ pip install sqlalchemy
# actualizar requirements.txt
$ pip freeze > requirements.txt # es necesario estar dentro del venv
# desactivar el entorno virtual
$ deactivate
```

4. Arrancar app.
```shell
$ fastapi dev main.py --reload
```