
<p align="center">
 <img width="30%" height="30%" src="https://user-images.githubusercontent.com/39133101/215219545-978e5749-c628-4cae-8fe0-9f23fdac417a.png">
</p>

<em><h1 align="center"> Hola "FastAPI" Mundo </h1></em>

<p align="center">
 <img src="https://img.shields.io/badge/Versi%C3%B3n-v1.0-green">
</p>

_Backend con PY y FastAPI._

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._


### Pre-requisitos 📋

_Para inicializar correctamente el proyecto, debes tener instalado lo siguiente:_

### virtualenv <p align="left"><img src="https://img.shields.io/badge/Virtualenv-v20.17.1-green"></p>

Es una herramienta para crear entornos virtuales aislados en Python.

Se instala con el siguiente comando:
```
pip install virtualenv
```
_virtualenv funciona con las siguientes implementaciones de intérpretes de Python:_

* CPython versions 3.7, 3.8, 3.9, 3.10, 3.11, 3.12

* PyPy 3.7, 3.8, 3.9

### FastAPI <p align="left"><img src="https://img.shields.io/badge/Fastapi-v0.89.1-green"></p>

FastAPI es un marco web moderno, rápido (de alto rendimiento) para crear API con Python 3.7+ basado en sugerencias de tipo estándar de Python.

Se instala con el siguiente comando:

```
pip instalar fastapi
```
### Uvicorn <p align="left"><img src="https://img.shields.io/badge/Uvicorn-v0.20.0-green"></p>

Uvicorn es una implementación de servidor web ASGI para Python.

Hasta hace poco, Python carecía de una interfaz mínima de servidor/aplicación de bajo nivel para marcos asíncronos. La especificación ASGI llena este vacío y significa que ahora podemos comenzar a crear un conjunto común de herramientas utilizables en todos los marcos asíncronos.

Uvicorn actualmente es compatible con HTTP/1.1 y WebSockets.

Se instala con el siguiente comando:

```
$ pip install uvicorn
```

### Instalación 🔧

_Una una vez se ralicen las instalaciones anteriores, se procede a clonar o descargar el repositorio._

_Después de abierto el repositorio, se procede a la crear un repositorio, el siguiente comando es utilziado para ello:_

```
virtualenv namevenv       
```

_Después de creado, se procede a activar el entorno virtual, el siguiente comando es utilizado para ello:_

```
source venv/bin/activate
```
o
```
venv\Scripts\activate.bat
```

_Para desactivar el entorno virtual, el siguiente comando es utilizado para ello:_

```
deactivate
```

_Una vez activado el entorno virtual de desarrollo, en el enlace de la ruta de archivos debe aparecer el nombre del entorno virtual entre paréntesis:_

```
(venv) PS C:\Users\venv\main.py>
```

_Una vez verificado el paso anterior, se debe escribir el siguiente comando en la consola:_

```
uvicorn main:app --reload
```

_Allí ya podrá ver en el siguiente enlace, el funcionamiento de FastApi:_

```
http://127.0.0.1:8000
```

## Construido con 🛠️

* [FastAPI](https://fastapi.tiangolo.com/)
* [Venv](https://docs.python.org/3/library/venv.html#module-venv)
* [Uvicorn](https://www.uvicorn.org/)

## Autores ✒️

* **Andrés Rodríguez** - *Educamas*
