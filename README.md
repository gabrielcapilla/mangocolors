# MangoCOLORS
**MangoCOLORS** es una colección de esquemas de color para [MangoHUD](https://github.com/flightlessmango/MangoHud). Estos esquemas están diseñados para hacer que MangoHUD sea más atractivo visualmente y mejorar su legibilidad al proporcionar un mejor contraste y diferenciación de colores.

## Pre instalación
Necesita tener instalado [MangoHUD](https://github.com/flightlessmango/MangoHud).

## Instalar
Simplemente, descarga los archivos y ejecute el archivo `.sh`.

# ¿Qué archivos encontrará?
En una fase temprana del proyecto encontrará una configuración global con distintos esquemas de color dentro de la carpeta **general** de cada tema. En la carpeta **perfiles** encontrará el archivo de configuración específico para distintos juegos con el esquema de color, posicion, tamaño y configuración de FPS.

# Perfiles

## Limite de FPS
Algunos perfiles utilizan el parametro `fps_limit` para limitar los FPS del juego. Este limite puede ser fijo o variable. Para las configuraciones variables con más de un limite de FPS, deberá usar el atajo **F9** para cambiar entre distintas velocidades de FPS.

### ¿Para que es útil el limite de FPS?
No todos los juegos necesitan funcionar a los mismos FPS. Como jugador diferenciamos los juegos de corte competitivo con juegos más pausados. No necesita jugar a más de 240 FPS en juegos como *Dota Underlords* o *Age Of Empire II*. Tampoco necesita jugar a más de 144 FPS juegos de modo historia como *Death Stranding* o *Tomb Raider*. Pero es necesario jugar a valores altos de FPS a juegos como *Apex Legends*. Es por eso que recomendamos hacer una clara distincion sobre el uso del limite de FPS para cada juego. 


### ¿Qué hace el archivo .sh?
El archivo `.sh` copia el archivo de configuración `MangoHud.conf` y lo pega en `~/.config/MangoHud/`. Para configuraciones concretas, se especifica el nombre del juego en el archivo de configuración. Puede cambiar el archivo de configuración mientras MangoHud se está ejecutando para poder ver los cambios en tiempo real.
