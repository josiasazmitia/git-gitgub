# Git & GitHub - Markdown y Magic Cells

![Logo de Git y GitHub](assets/logos-git-github.png "Logo de Git y GitHub")


## ¿Qué es Git?

Git es un sistema de control de versiones distribuido diseñado para manejar todo, desde proyectos pequeños a muy grandes con velocidad y eficiencia. Facilita a los desarrolladores el seguimiento de los cambios en el código fuente durante el desarrollo de software.

Git es un software de control de versiones gratis y de código abierto. Fue creado por Linus Torvalds en 2005. Esta herramienta es un sistema de control de versiones que fue inicialmente desarrollado para trabajar con varios desarrolladores en el núcleo de Linux.

## ¿Qué es un sistema de control de versiones y Git?

Un sistema de control de versiones o VCS (Version Control System, por sus siglas en inglés), rastrea el historial de cambios conforme las personas y los equipos colaboran juntos en los proyectos. Conforme los desarrolladores hacen cambios al proyecto, cualquier versión anterior de este puede recuperarse en cualquier momento.

Los desarrolladores pueden revisar el historial de proyectos para averiguar:

¿Qué cambios se hicieron?
¿Quién los hizo?
¿Cuándo se hicieron?
¿Por qué se necesitaban?

Los VCS le proporcionan a cada contribuyente una vista consistente y unificada de un proyecto, lo cual muestra el trabajo que ya está en progreso. El ver un historial de cambios transparente, quién los hizo y cómo contribuyen al desarrollo de un proyecto, ayuda a que los miembros de los equipos se alineen mientras trabajan independientemente.

En un sistema de control de versiones distribuido, cada desarrollador tiene una copia integral del proyecto y del historial del mismo. A diferencia de los sistemas de control de versiones centralizados populares, los DVCS necesitan una conexión constante a un repositorio central. Git es el sistema de control de versiones distribuido más popular. Git se utiliza habitualmente tanto para el desarrollo de proyectos de código abierto como comerciales y tiene beneficios significativos para los individuos, equipos y negocios.

Git permite que los desarrolladores vean la línea de tiempo completa para los cambios, decisiones y progresión de cualquier proyecto en un solo lugar. Desde el momento en el que acceden al historial de un proyecto, el desarrollador tiene todo el contexto que necesitan para entenderlo y comenzar a contribuir.

Los desarrolladores trabajan en todos los husos horarios. Con un DVCS como Git, las colaboraciones pueden tomar lugar en cualquier momento, mientras se mantiene la integridad del código fuente. Al utilizar las ramas, los desarrolladores pueden proponer cambios al código de producción de forma segura.

Los negocios que utilizan Git pueden derribar las barreras de comunicación entre los equipos y mantenerlos enfocados en que realicen su mejor trabajo. Además, Git permite alinear a expertos a lo largo de los negocios para que colaboren en los proyectos principales.

### Acerca de los repositorios
Un repositorio o proyecto de Git comprende toda la colección de archivos y carpetas asociados con un proyecto, en conjunto con el historial de revisión de cada archivo. El historial del archivo se muestra como capturas de pantalla en el tiempo, las cuales se denominan "confirmaciones". Estas confirmaciones pueden organizarse en varias líneas de desarrollo, llamadas "ramas". Ya que Git es un DVCS, los repositorios son unidades auto-contenidas y cualquiera que tenga una copia del repositorio puede acceder a toda la base de código y a su historial. Utilizando la línea de comandos o cualquier otra interfaz de facilidad de uso, un repositorio de Git también permite: interactuar con el historial, clonar el repositorio, crear ramas, confirmar, fusionar y comparar cambios entre las versiones del código y más.

A través de plataformas como GitHub, Git también proporciona más oportunidades para la transparencia y colaboración en los proyectos. Los repositorios públicos hacen que los equipos trabajen en conjunto para crear el mejor producto final posible.

### Características clave:

- **Control de versiones:** Gestión de las diferencias en el código fuente a lo largo del tiempo.
- **Distribuido:** Cada desarrollador trabaja con una copia completa del repositorio.
- **Seguridad:** Utiliza criptografía SHA-1 para asegurar la integridad del código fuente.

## ¿Qué es GitHub?

GitHub es una plataforma de alojamiento de código basada en la web que utiliza Git. Permite a los desarrolladores colaborar en proyectos, hacer seguimiento de problemas, y más.

hospeda repositorios de Git y proporciona a los desarrolladores las herramientas para generar un código mejor mediante características de línea de comandos, propuestas (debates en hilo), solicitudes de cambio, revisión de código o el uso de un conjunto de apps gratuitas y de pago en GitHub Marketplace. Con las capas de colaboración tales como el flujo de GitHub, una comunidad de 100 millones de desarrolladores y un ecosistema con cientos de integraciones, GitHub cambia la forma en la que se crea el software.

GitHub crea una colaboración directamente en el proceso de desarrollo. El trabajo se organiza en los repositorios donde los desarrolladores pueden describir los requisitos o la dirección y marcar las expectativas para los miembros de los equipos. Posteriormente, utilizando el flujo de GitHub, los desarrolladores simplemente crean una rama para trabajar en las actualizaciones, confirmar cambios para guardarlos, abrir una solicitud de cambios para proponerlos y debatirlos y fusionar solicitudes de cambio una vez que todos estén de acuerdo.

![branches](assets/branches.png "branches")

### Características:

- **Repositorios:** Almacenamiento del código fuente y su historial.
- **Forking y Pull Requests:** Permiten contribuir a proyectos y sugerir cambios.
- **Gestión de proyectos:** Herramientas como seguimiento de problemas y wikis.

### GitHub y la línea de comandos

#### Comandos básicos de Git
Para utilizar Git, los desarrolladores utilizan comandos específicos para copiar, crear, cambiar y combinar el código. Estos comandos pueden ejecutarse directamente desde la línea de comandos o utilizando una aplicación como GitHub Desktop. Aquí tienes algunos comandos comunes para utilizar Git:

```git init``` inicializa un repositorio nuevo de Git y comienza a supervisar el directorio existente. Este agrega una subcarpeta oculta dentro del directorio existente que hospeda la estructura de datos interna que se requiere para el control de versiones.

```git clone``` crea una copia local de un proyecto que ya existe remotamente. El clon incluye todos los archivos, historial y ramas del proyecto.

```git add``` almacena provisionalmente un cambio. Git rastrea los cambios que se hacen a la base de código de un desarrollador, pero es necesario probarlos y tomar una captura de pantalla de ellos para incluirla en el historial del proeycto. Este comando realiza pruebas, la primera parte de este proceso de dos pasos. Cualquier cambio que se pruebe, se convertirá en parte de la siguiente captura de pantalla y también del historial del proyecto. Las pruebas y confirmaciones por separado otorgan a los desarrolladores el control completo sobre el historial y sobre el proyecto sin cambiar la forma en la que codifican y trabajan.

```git commit``` guarda la instantánea del historial del proyecto y completa el proceso de seguimiento de los cambios. En resumen, una confirmación funciona tal como el tomar una fotografía. Todo lo que se haya almacenado provisionalmente con ```git add``` pasará a formar parte de la instantánea con git commit.

```git status``` muestra el estado de los cambios como sin seguimiento, modificados o almacenados provisionalmente.

```git branch``` muestra las ramas en las que se trabaja localmente.

```git merge``` combina las líneas de desarrollo. Este comando habitualmente se utiliza para combinar los cambios que se realizan en dos ramas distintas. Por ejemplo, un desarrollador podría hacer una fusión cuando necesite combinar los cambios de una rama de característica en la rama de desarrollo principal.

```git pull``` actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlos en su ambiente local.

```git push``` actualiza el repositorio remoto con las confirmaciones realizadas localmente en una rama.

#### Ejemplo de un Repositorio en GIT
```bash
# download a repository on GitHub to our machine
# Replace `owner/repo` with the owner and name of the repository to clone
git clone https://github.com/owner/repo.git

# change into the `repo` directory
cd repo

# create a new branch to store any new changes
git branch my-branch

# switch to that branch (line of development)
git checkout my-branch

# make changes, for example, edit `file1.md` and `file2.md` using the text editor

# stage the changed files
git add file1.md file2.md

# take a snapshot of the staging area (anything that's been added)
git commit -m "my snapshot"

# push changes to github
git push --set-upstream origin my-branch
```

## Markdown y sus comandos

Markdown es un lenguaje de marcado ligero para crear contenido en plataformas como GitHub.

### Comandos básicos:

- `# Título 1`, `## Título 2`, ... para encabezados.
- `*texto en cursiva*`, `**texto en negrita**` para formato de texto.
- `[Texto del enlace](URL)` para enlaces.
- `![Texto alternativo](URL de la imagen)` para imágenes.
- `-` o `*` para listas no ordenadas, y `1.`, `2.`, etc., para listas ordenadas.
- ``` para bloques de código.

## Magic Cells

En el contexto de Jupyter Notebooks, las "celdas mágicas" son comandos especiales que extienden la funcionalidad básica del notebook.

### Ejemplos:

- `%matplotlib inline`: Para mostrar gráficos dentro del notebook.

- [Ver el ejemplo de Magic Cells](https://github.com/josiasazmitia/git-gitgub/blob/master/MagicCellsExamples.ipynb)
- [Ver el mismo ejemple de Magic Cells en notebooks.gesis.org](https://notebooks.gesis.org/binder/jupyter/user/josiasazmitia-git-gitgub-k1hvhicx/lab/tree/MagicCellsExamples.ipynb)


---

© 2024 Josias Chocooj | Carnet: 24000705 | [Contacto](mailto:josias.azmitia@galileo.edu)