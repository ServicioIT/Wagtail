# Wagtail
## Sistema de gestión de contenidos para Django, enfocado en la flexibilidad y la experiencia del usuario.

### Requisitos iniciales:

- Git command (sudo apt install git-all)
- Python > 3.8 < 3.11 (https://www.python.org/downloads/)
- Pip > (python -m ensurepip --upgrade)
- VirtualENV (pip3 install virtualenv)
- Docker core (opcional)

### Instalación:

Clonación del repositorio
```javascript
git clone https://github.com/ServicioIT/Wagtail.git
```
ve al directorio donde se descargo el Git
```javascript
cd Wagtail
```
Creacion de entorono virtual
```javascript
python3 -m venv venv
```
activacion del entorno virtual (venv)
```javascript
source venv/bin/activate
```
instalacion de requerimientos en el entorno virtual
```javascript
pip install -r requirements/development.txt 
```
ejecución del servidor de pruebas
```javascript
python3 manage.py runserver
```
Visita en tu navegador web: http://127.0.0.1:8000/

![Alt text](https://cdn.hashnode.com/res/hashnode/image/upload/v1668768006851/MHnlHAWmd.png?auto=compress,format&format=webp)

### Ejecutar en Docker:
```javascript
cd ~/Wagtail/cms/
```
```javascript
docker build -t cms .
```
```javascript
docker run -p 8000:8000 cms
```
Visita en tu navegador web: http://127.0.0.1:8000/

Credenciales de administración:
- usuario: admin
- contraseña: admin2024

> Este proyecto es un demo en español de [WIGTAIL](https://github.com/wagtail/wagtail).

