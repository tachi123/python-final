Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

 ¿Qué es pip?
pip es un administrador de paquetes para Python. Su nombre es un acrónimo recursivo que significa "Pip Installs Packages". Es la herramienta recomendada para instalar y gestionar bibliotecas y dependencias en proyectos de Python.

Funciones principales de pip
Instalación de paquetes: Permite instalar paquetes desde el Índice de Paquetes de Python (PyPI) y otras fuentes.
Desinstalación de paquetes: Permite eliminar paquetes que ya no son necesarios.
Gestión de dependencias: Se asegura de que todas las dependencias requeridas por un paquete se instalen automáticamente.
Actualización de paquetes: Permite actualizar paquetes instalados a sus versiones más recientes.
Listar paquetes instalados: Muestra una lista de todos los paquetes instalados en el entorno de Python.
¿Por qué actualizamos pip?
Actualizar pip es una práctica recomendada por varias razones:

Nuevas funcionalidades: Las versiones más recientes de pip a menudo incluyen nuevas características que pueden mejorar la experiencia del usuario.
Corrección de errores: Las actualizaciones pueden resolver errores y problemas de versiones anteriores.
Mejoras de seguridad: Las versiones nuevas pueden incluir parches de seguridad importantes que protegen tu entorno y código.
Compatibilidad: Asegura la compatibilidad con las versiones más recientes de Python y otros paquetes. 

13. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

14. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
