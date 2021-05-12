- Instalacion de MySQL con python

Se busca lograr crear conexion entre la base de datos de MySQL con Python 
esto a travez de Xampp trabajando en conjunto con php

Pasos que seguir 
1. Instalaciones
    - Intalamos MYySQL y Worckbench
    - Instalaremos la conexion con MySQL  con el siguiente codigo (pip install mysql-connector-python)
    - Instalaremos Pandas con el sigueinte codigo (pip install pandas)
2. Importar librerias
    - Importaremos las siguientes bibliotecas que son las que nos ayudaran a realizar la conexion 
    import mysql connector
    from mysql.connector import Error
    import pandas as pd
3. Conectar el servidor y la Base de datos
    - Realizaremos la conexion con la BD
    - Creamos una nueva base de datos
    - Modificar y crear la funcion de conexion con la base de datos
    - Defnimos las funciones de consulta
4. Creacion de tablas en la base de datos
    - Creamos la primera tabla para comprobar que se realiza la conexion y lo que ingresamos
    - Creamos el resto de las tablas 
    - Definir relaciones de clave externa
5. Rellenar las tablas de la base de datos
    - Llenamos datos en la primera tabla para confirmar conexion y que se ingresan los datos
    - Llenamos el resto de las tablas 
6. Leer los datos de la base de datos
    - Definir la función de lectura de datos
    - Leer datos de la base de datos