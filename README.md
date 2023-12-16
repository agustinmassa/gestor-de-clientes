# GESTOR DE CLIENTES
Este proyecto es desarrollado en python y consiste en un gestor de clientes. En el cual listamos los clientes del gestor, consultamos un cliente a partir del dni, 
agregamos un cliente con campos (nombre, apellido, dni), modificamos el nombre y apellido de un cliente a partir del dni, borramos un cliente a partir del dni y
salimos del programa.

# Organización
Los cuatro ficheros básicos:

run.py: El script principal que lo pondrá todo en marcha.

menu.py: La interfaz que mostrará por la terminal un menú.

database.py: Encargado de manejar la gestión de los datos.

helpers.py: Contendrá funciones auxiliares de uso general.

# Para probar el programa en modo gráfico
python run.py
# Para probar el programa en modo terminal
python run.py -t
# Para ejecutar las pruebas unitarias
pytest -v
