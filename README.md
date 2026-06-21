# TPE WEB 2 - Sistema de Gestión de Equipos y Jugadores

## Integrante

- Juan Ignacio Arballo
- DNI: 46825856
- Email: jiarballo6@gmail.com

## urls

## jugador

- login (JWT): POST/http://localhost/tpe_parte_3_2026/api_router.php?resource=auth/login

Username es admin y password admin.

- listar jugadores: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores

- listar jugador por id: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores/id

- filtrado: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&filterField=id_equipo&filterValue=1

- para comprobar el campo de filtro invalido: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&filterField=hack&filterValue=1

- ORDENAMIENTO:

- ascendente: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&sort=precio&order=ASC

- descendente: GET/http://localhost/tpe_parte_3_2026/api_router.php?resource=jugadores&sort=id&order=DESC

en la parte de "precio&order" se puede cambiar el valor de precio para elegir otro caracter para ordenar como id, nombre, id_equipo, etc".



