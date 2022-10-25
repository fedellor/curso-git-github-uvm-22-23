# Curso de Git y GitHub

Curso de Git y GitHub para la fase de ampliación de UVigo Motorsport 2022 - 2023.

## Introducción

### ¿Qué es Git?

Git es un sistema de control de versiones distribuido, es decir, que cada usuario tiene una copia completa del repositorio. Esto permite que cada usuario pueda trabajar de forma independiente sin necesidad de estar conectado a internet.

* [Enlace de descarga](https://git-scm.com/downloads)

### ¿Qué es GitHub?

GitHub es una plataforma de desarrollo colaborativo que permite alojar proyectos utilizando el sistema de control de versiones Git. Además, GitHub cuenta con una serie de herramientas que facilitan el trabajo en equipo.

Esencialmente, GitHub es una red social para desarrolladores. En ella, los usuarios pueden crear repositorios públicos o privados, donde alojar sus proyectos. Además, GitHub permite que los usuarios puedan colaborar en los proyectos de otros usuarios de manera remota.

GitHub es, como tal, una plataforma web, pero también dispone de una aplicación de escritorio que permite trabajar con los repositorios de manera local y eficiente.

* [Página de inicio](https://github.com)
* [Enlace de descarga](https://desktop.github.com/)

### Entonces... ¿Git es lo mismo que GitHub?

No. Git es un sistema de control de versiones, mientras que GitHub es una plataforma de desarrollo colaborativo que utiliza Git como base.

## Funcionalidades principales de Git/GitHub

### Repositorios: el corazón de las versiones

Un repositorio es un espacio donde se almacenan los archivos de un proyecto. En GitHub, los repositorios se almacenan en la nube, por lo que no es necesario que cada usuario tenga una copia completa del repositorio.

En el caso de Git, al tratarse de una herramienta local, los repositorios serían aquellos directorios que contienen los archivos de un proyecto y están inicializados con Git (mediante un archivo `.git`).

### Branches: organiza el desarrollo

Un branch es una **rama de desarrollo alternativa de un repositorio**. Los branches se utilizan para crear una copia de un repositorio en el que se pueda trabajar de forma independiente sin afectar al repositorio original.

La rama principal de cada repositorio suele denominarse `main` o `master`.

### Commits: guarda tu trabajo

Un commit es un **conjunto de cambios realizados en un repositorio**. Cada commit tiene asociado un *tag* único, que permite identificar de forma única el conjunto de cambios que contiene.

Los commits se componen de dos partes: título y resumen. El título debe ser un resumen claro y conciso de los cambios realizados en el commit. El resumen es opcional y debe ser utilizado para explicar con más detalle los cambios realizados.

### Push: consolida tus cambios

Un push es un **comando que permite subir los cambios realizados en un repositorio local** a un repositorio remoto.

Cuando se dispone de una serie de cambios locales (uno o varios commits), se puede subir el conjunto de cambios al repositorio remoto mediante un push.

### Pull: obtén los cambios de otros

Un pull es un **comando que permite descargar los cambios realizados en un repositorio remoto** a un repositorio local.

En caso de que se haya realizado un push a un repositorio remoto, los cambios realizados en el repositorio remoto no se verán reflejados en el repositorio local hasta que se realice un pull.

### Clone: copia un repositorio

Un clone es un **comando que permite copiar un repositorio remoto** a un repositorio local.

La copia no tiene funcionalidad de contribución, es decir, no se puede realizar un push a un repositorio clonado.

`git clone https://github.com/user/repo`

### Forks: si lo puedes *forkear*, es todo tuyo

Un fork es una **copia de un repositorio**. Los forks se utilizan para crear una copia en la que se pueda trabajar de forma independiente sin afectar al repositorio original.

### Pull requests: la esencia de la colaboración

Una pull request es una **solicitud de incorporación de cambios realizados en un repositorio a otro repositorio**. Las pull requests se utilizan para solicitar la incorporación de cambios realizados en un repositorio a otro repositorio.

### Merge requests: acepta contribuciones

Una merge request es un **comando que permite incorporar los cambios realizados en un repositorio a otro repositorio**. Debe ser aceptado por un administrador del repositorio para que los cambios se incorporen.

### Merge conflicts: ¿esto funciona?

Un merge conflict es un **conflicto que se produce al intentar incorporar los cambios realizados en un repositorio a otro repositorio**. Los merge conflicts se producen cuando dos o más usuarios realizan cambios en el mismo archivo y se intenta incorporar los cambios a un repositorio.

## Funcionalidades de GitHub

### Issues: reporta problemas

Una issue es un **reporte de un problema**. Los issues se utilizan para reportar problemas en un repositorio.

Asimismo, las issues se pueden utilizar para solicitar nuevas funcionalidades o para realizar sugerencias; no necesariamente tiene que existir un error para que se cree una issue.

### Projects: organiza tu trabajo

Un project es un **conjunto de issues organizado y clasificado**. Los projects se utilizan para organizar el trabajo en un repositorio.

Cada elemento de un project puede tener una serie de atributos, como el estado, la prioridad, el responsable, etc.

Los projects tienen dos tipos de visualización: en tabla y en etiquetas. En la visualización en tabla, los elementos se organizan en filas (cada fila es un elemento nuevo, siendo sus columnas los atributos que tenga), mientras que en la visualización en etiquetas, los elementos se organizan en tipos de opciones para una etiqueta concreta (estado: por hacer, en progreso, hecho).

### Wiki: documenta tu proyecto

Una wiki es una **página de documentación del repositorio**. Las wikis se utilizan para aportar información adicional de cara al público para comprender el uso del repositorio y de sus contenidos.

### Pages: publica tu proyecto

Una page es una **página web asociada a un repositorio**. Las pages se utilizan para publicar un proyecto de cara al público.

Permiten diseñar y estilizar una página web sencilla y personalizada, que puede ofrecer funcionalidades ligadas al objetivo del proyecto (como, por ejemplo, implementar sus contenidos de manera interactiva).

* [Vector Field Play](https://anvaka.github.io/fieldplay/)

### Actions: automatiza tu trabajo

Una action es una **automatización de un proceso**. Las actions se utilizan para realizar de forma automática un proceso cuando se produce un evento determinado, como puede ser el hecho de que se realice un push a un repositorio o produzca una pull request.

### Marketplace: encuentra herramientas

El marketplace es un **catálogo de herramientas**. El marketplace se utiliza para encontrar funcionalidades adicionales que se pueden incorporar a un repositorio.

Dichas funcionalidadades engloban desde diseño básico de los elementos del repositorio hasta propias series de actions personalizadas con funcionalidad compleja.

### Releases: publica versiones

Una release es una **versión oficial de un repositorio**. Las releases se utilizan para definir versiones estables de desarrollo en un repositorio
