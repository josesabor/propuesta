% "MyPlayList"
% José María Saborido Monge
% Curso 2019/20

# Descripción general del proyecto

MyPlayList será una aplicacion web en la que podras registrar todos los juegos que vayas completando ademas de poder ver los juegos que completan tus amigos. 

Los usuarios logeados podran ver sus juegos, poner juegos en su lista de juegos pendientes y enviar y aceptar sugerencias de juegos a completar.

El usuario final tambien dispondra de un apartado de estadisticas en el cual podra ver por ejemplo cuantos juegos por género o cuantos juegos por plataforma ha completado el usuario.


## Funcionalidad principal de la aplicación

La funcionalidad principal será mantener un registro de todos los juegos completados por el usuario.

## Objetivos generales

* Objetivo: "Gestionar los juegos completados de cada usuario, así como interactuar con otros mediante comentarios y sugerencias".

* Casos de uso: 
    *  Usuarios no logueados
        "Home", "Iniciar sesion", "Registrarse", "Ver indice de otro usuario", "Ver detalles de juego","Ver detalles de juego completado", "Filtrado en el indice", "Ver estadisticas de otro usuario", "Buscar a otro usuario", "Ver Juegos por plataforma", "Ver juegos por genero" y "Ver Estadisticas de usuarios". 
     *  Usuarios logueados
        Todos los anteriores, "Crear lista", "Añadir juego completado",  "Modificar dato de entrada de juego completado", "Borrar entrada de juego completado", "Alternar entre perfil privado y público", "Seguir a un usuario", "Enviar solicitud de seguimiento", "Recomendar juego a usuario", "Enviar mensaje a usuario", "Reportar una incidencia", "Comentar a otro usuario" y "Cerrar sesion".
    *  Administradores
        Todos los anteriores, "Recibir incidencias", "Editar entradas" y "Modificar juego".

# Elemento de innovación

Uso de la API de [IGDB](https://api.igdb.com/) para obtener datos adicionales de todos los juegos.
