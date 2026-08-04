# Codedex.io — Landing page informativa

Página web estática en español que presenta qué es [Codedex.io](https://www.codedex.io/) y cómo ayuda a aprender programación de forma práctica e interactiva.

El diseño usa una estética elegante en modo oscuro y está adaptado para pantallas de escritorio y móviles.

## Contenido

- Introducción a Codedex.io.
- Explicación de sus cursos, ejercicios, proyectos y comunidad.
- Sección con una ruta de aprendizaje sencilla.
- Diseño responsive y navegación interna suave.

## Tecnologías

- HTML5
- CSS3
- Google Fonts: Manrope y DM Mono

## Estructura del proyecto

```text
.
├── index.html   # Estructura y contenido de la página
├── styles.css   # Estilos visuales y diseño responsive
└── README.md    # Documentación del proyecto
```

## Cómo visualizarlo

Abre el archivo `index.html` en tu navegador web. No requiere instalación de dependencias ni un servidor.

## Comandos de Git

### `git config --global user.name`

Consulta el nombre de autor configurado globalmente en Git. Para establecerlo, añade el nombre entre comillas, por ejemplo: `git config --global user.name "Tu Nombre"`.

### `git config --global user.email`

Consulta el correo electrónico de autor configurado globalmente en Git. Para cambiarlo, usa un correo entre comillas, por ejemplo: `git config --global user.email "tu-correo@ejemplo.com"`.

### `git init`

Inicializa un repositorio de Git en la carpeta actual. Git empieza a registrar el historial de cambios del proyecto.

### `git remote add origin <repository_url>`

Conecta el repositorio local con uno remoto y le asigna el nombre `origin`. Sustituye `<repository_url>` por la URL de tu repositorio, por ejemplo, el de GitHub.

### `git branch -M main`

Renombra la rama actual a `main`. La opción `-M` fuerza el cambio si ya existe una rama con ese nombre.

### `git add .`

Agrega todos los archivos nuevos y las modificaciones de la carpeta actual al área de preparación (*staging area*) para incluirlos en el siguiente commit.

### `git commit -m 'Your commit message here!'`

Guarda los cambios que están en el área de preparación en el historial local de Git. Reemplaza el texto entre comillas por un mensaje breve y descriptivo, por ejemplo: `git commit -m "Agrega página informativa de Codedex"`.

### `git commit --amend --reset-author`

Reemplaza el último commit local y actualiza su autor con el nombre y correo configurados actualmente en Git. Normalmente abre el editor para conservar o modificar el mensaje del commit. Úsalo antes de enviar ese commit al repositorio remoto; si ya fue publicado, reescribirás su historial y necesitarás coordinarlo con el equipo.

### `git status`

Muestra el estado actual del repositorio: archivos modificados, archivos pendientes de agregar y cambios listos para confirmar.

### `git push -u origin main`

Envía la rama local `main` al repositorio remoto llamado `origin`. La opción `-u` establece esa rama remota como referencia predeterminada para futuros comandos `git push` y `git pull`.
