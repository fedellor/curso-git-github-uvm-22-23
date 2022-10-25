# Proyecto curso de Git y GitHub

Documentación del proyecto del curso de Git y GitHub para la fase de ampliación de UVigo Motorsport 2022 - 2023.

## Planteamiento

En este proyecto se llevarán a cabo dos fases que permitirán explorar toda la funcionalidad relevante que Git y GitHub ponen a disposición del usuario.

*Aviso: para llevar a cabo los ejercicios de este proyecto es imprescindible tener Git instalado en el ordenador que se esté usando.*

## Fase 1: planificación

Instrucciones:

1. Crear un repositorio en GitHub con el nombre `curso-git-github-iniciales`, donde `iniciales` tiene que ser sustituido por las iniciales de tu nombre y tus apellidos (en minúscula).
2. Crear un proyecto (versión nueva, no clásica) que utilizarás para llevar a cabo los ejercicios de esta fase. El estilo del proyecto debe ser de tipo tabla
3. Crear una vista de tipo etiqueta con la clasificación de elementos del proyecto por estado de desarrollo (por hacer, en proceso, hecho)
4. Asociar el proyecto a tu repositorio de GitHub
5. Añadir un atributo de los elementos del proyecto que represente la fecha máxima de realización de dicho elemento
6. Añadir un atributo de los elementos del proyecto que represente una descripción de dicho elemento
7. Crear una entrada del proyecto para cada punto que se indica en el apartado de desarrollo interno de la fase 2. Asegúrate de asociar cada entrada con el repositorio que acabas de crear. Podrás ponerle un nombre llamativo y una descripción que te ayude a identificarlo.
8. Según vayas realizando los ejercicios de la fase 2, marca como realizada cada entrada del proyecto.

## Fase 2: desarrollo

### Desarrollo propio

Instrucciones:

1. Asegúrate de que tu repositorio es público
2. Crear una branch llamada `devel` en el repositorio. Establecer dicha rama como rama de trabajo actual
3. Editar README.md y añadir un título y una descripción del proyecto, la que veas más conveniente y adecuada
4. Crear archivo llamado `execute-me.py` que contenga la instrucción `print("Hello World!")`
5. Crear archivo llamado `execute-me.sh` dentro de una carpeta denominada `other` que contenga la instrucción `echo "Hello World!"`
6. Crear actions personalizada que ejecute los programas de los puntos 4 y 5 de forma automática cuando se realiza un commit o una pull request
7. Unir los cambios de la rama `devel` a la rama principal del repositorio
8. Llevar a cabo una release oficial del repositorio denominada `v1.0.0`

Una vez esté creado vuestro repositorio, podréis pasar a la siguiente fase.

### Colaboración externa

Instrucciones:

1. Hacer un fork del repositorio base del curso (<https://github.com/erlete/curso-git-github-uvm-22-23>).
2. Crear una brach denominada `devel-iniciales`, donde `iniciales` tiene que ser sustituido por las iniciales de tu nombre y tus apellidos (en minúscula).
3. Editar el `README.md` como se indica en el mismo
4. Establecer dicha rama como rama de trabajo actual
5. Añadir los archivos de los tres notebooks realizados a un directorio llamado `notebooks`. Añadir los archivos del proyecto final (si se ha realizado a parte) a un directorio llamado `project`.
6. Crear un archivo de texto llamado `review.txt` donde incluyas una pequeña valoración de los cursos en los que hayas participado hasta ahora.
7. Realizar una pull request desde la rama de `devel-iniciales` al repositorio original
