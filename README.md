
cereixeira.github.io/es

El proyecto publica en la dirección https://cereixeira.github.io/es/

La idea es publicar en esta dirección el contenido de la carpeta "es" del repositorio, que contiene el contenido en español. 
El contenido en inglés se publicará en la dirección https://cereixeira.github.io/en/ y se encuentra en la carpeta "en" del repositorio.

El proceso comienza desde el proyecto cereixeira-frontend, al hacer push
se ejecuta un workflow de GitHub Actions que construye el proyecto y luego copia el contenido de la carpeta "es" a la carpeta "es" del repositorio cereixeira.github.io, y lo mismo para la carpeta "en".
Luego se hace un commit y push este mismo repo "ceixeira.github.io", lo que hace que se publique el contenido en las direcciones mencionadas anteriormente.