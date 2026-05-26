# GitHub Practice

Este proyecto fue realizado unicamente para la Clase 17 del Módulo 2, correspondiente al aprendizaje sobre el uso de Git y GitHub en un flujo de trabajo colaborativo.

## Descripción del proyecto

El proyecto consiste en una página web sencilla con temática veterinaria, enfocada en intereses personales entre elos  bienestar animal, prevención de zoonosis y uso responsable de la tecnología para documentar el desarrollo de una página web.

La finalidad principal no es crear una página compleja, sino demostrar el manejo de herramientas como Git, GitHub, ramas, commits, repositorio remoto, Pull Request y documentación en Markdown.

## Funcionalidades implementadas

- Creación de un archivo `index.html`.
- Creación de un archivo `style.css`.
- Diseño de una barra de navegación.
- Uso de secciones informativas.
- Aplicación de colores pastel relacionados con medicina veterinaria.
- Uso de diseño responsivo básico.
- Documentación mediante archivo `README.md`.

## Ramas utilizadas

- `main`: rama principal del proyecto.
- `feature/navbar`: rama creada para agregar y modificar la barra de navegación.

## Comandos principales utilizados

```bash
git init
git status
git add .
git commit -m "Commit inicial del proyecto"
git branch -M main
git remote add origin (+URL)
git push -u origin main
git checkout -b feature/navbar
git add .
git commit -m "Agrega navbar y estructura visual"
git push -u origin feature/navbar
git checkout main
git merge feature/navbar
git push origin main

## Flujo de trabajo realizado

Para este proyecto se utilizó Git y GitHub con el objetivo de practicar un flujo de trabajo colaborativo. Primero se creó un repositorio local con los archivos iniciales del proyecto. Luego se realizó el primer commit y se conectó el repositorio local con un repositorio remoto en GitHub.

Posteriormente, se creó la rama `feature/navbar` para trabajar una mejora específica en la barra de navegación del archivo `index.html`. Esta rama fue subida al repositorio remoto y luego se creó un Pull Request desde GitHub para comparar los cambios con la rama principal `main`.

Finalmente, el Pull Request fue revisado, fusionado correctamente con `main` y cerrado. Esto permitió simular un flujo de trabajo colaborativo, usando ramas, commits, push, Pull Request y merge.

## Reflexión personal

Este trabajo me permitió comprender de forma más práctica cómo se utiliza GitHub dentro de un proyecto de desarrollo web. Aunque el proyecto es sencillo, me ayudó a practicar acciones importantes como crear ramas, realizar commits, subir cambios al repositorio remoto y fusionarlos mediante un Pull Request.

Además, personalicé el contenido con una temática relacionada con medicina veterinaria, bienestar animal y prevención de zoonosis, integrando mis intereses personales con el aprendizaje técnico del módulo.