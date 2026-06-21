# TPE WEB 2 - Sistema de Gestión de Equipos y Jugadores

## Integrante

- Juan Ignacio Arballo
- DNI: 46825856
- Email: jiarballo6@gmail.com

## urls

## jugador

# login (JWT): 

- POST/http://localhost/tpe_parte_3_2026/api_router.php?resource=auth/login

body:{
    "username": "webadmin",
    "password": "admin"
}

# listar jugadores: 

- listar todos: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores

- listar jugador por id: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores/id

# filtrado: 

- GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&filterField=id_equipo&filterValue=1

# para comprobar el campo de filtro invalido: 

- GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&filterField=hack&filterValue=1

# ORDENAMIENTO:

- ascendente: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&sort=precio&order=ASC

- descendente: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&sort=id&order=DESC

en la parte de "precio&order" se puede cambiar el valor de precio para elegir otro caracter para ordenar como id, nombre, id_equipo, etc.

# PAGINADO: 

- pagina 1: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&page=1&limit=3

- pagina 2: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&page=2&limit=3

# POST sin token:

- POST/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores

- body: {
    "nombre":"messi",
    "precio":5000000.00,
    "id_equipo":2,
    "id_posicion":4
}

# POST con token:

- token:eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6MSwidXNlcm5hbWUiOiJ3ZWJhZG1pbiIsImV4cCI6MTc4MjAzNjI1NH0.rToK9HkaV7zXl7SQJx5Oe-olDFHtiC9iKHvGowcuzJQ

# 


