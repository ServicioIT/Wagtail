# Wagtail
## Sistema de gestión de contenidos para Django, enfocado en la flexibilidad y la experiencia del usuario.

### Requisitos:

- Git command
- Python > 3.9
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
pip install -r requirements.txt
```
ejecución del servidor de pruebas
```javascript
python manage.py runserver
```

Visita en tu navegador web: http://127.0.0.1:8000/

![Alt text](https://docs.wagtail.org/en/stable/_images/tutorial_1.png)

### Instalación en Docker:
- docker build -t cms .
- docker run -p 8000:8000 cms

Visita en tu navegador web: http://127.0.0.1:8000/

Credenciales de administración:
- usuario: admin
- contraseña: admin2024

> Este proyecto es un demo en español de [WIGTAIL](https://github.com/wagtail/wagtail).

