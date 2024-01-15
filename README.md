# Wagtail
Sistema de gestión de contenidos para Django, enfocado en la flexibilidad y la experiencia del usuario.

Requisitos:

- Git command
- Python > 3.9
- Docker core (opcional)

Instalación:
- git clone https://github.com/ServicioIT/Wagtail.git (Clonación del repositorio)
- cd Wagtail (dirfectorio donde se descargo el Git)
- python3 -m venv venv (Creacion de entorono virtual)
- source venv/bin/activate (activacion del entorno virtual)
- pip install -r requirements.txt (instalacion de requerimientos en el entorno virtual)
- python manage.py runserver (Ejecución del servidor de pruebas)

Visita en tu navegador web: http://127.0.0.1:8000/

https://docs.wagtail.org/en/stable/_images/tutorial_1.png

Instalación en Docker:
- docker build -t cms .
- docker run -p 8000:8000 cms

Visita en tu navegador web: http://127.0.0.1:8000/

Credenciales de administración:
- usuario: admin
- contraseña: admin2024

Este proyecto es un demo en español de: https://github.com/wagtail/wagtail

