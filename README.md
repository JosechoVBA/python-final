
# Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 
```sh
mkdir python-final
```
3. Entramos en ella: 
```sh
cd python-final
```
4. Iniciamos el repositorio:
```sh
git init
```
5. Creamos un archivo:
```sh
touch finales.py
```
6. Abrimos VSC:
```sh
code .
```
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V

python3 -V
```
8. Creamos el entorno virtual en Python:
```sh
python3 -m venv venv #Creamos el entorno virtual
```
9. Activamos el entorno virtual:
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
```
10. Hacemos actualización del pip de Python
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
11. Investigar ¿Qué es el pip y porque lo actualizamos?

**Pip** es el gestor de paquetes para Python, utilizado para __instalar y gestionar__ paquetes de software adicionales que no forman parte de la biblioteca estándar de Python. Una "actualización de pip" se refiere a la acción de actualizar pip a la última versión disponible. Mantener pip actualizado es importante porque las nuevas versiones suelen incluir mejoras, correcciones de errores y nuevas características.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.