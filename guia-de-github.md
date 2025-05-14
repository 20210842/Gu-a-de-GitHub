# Guía Básica de GitHub: Issues y Pull Requests

Esta guía te ayudará a comprender dos funciones clave de GitHub: **Issues** y **Pull Requests**. Son herramientas esenciales para colaborar en proyectos, gestionar tareas y mantener un flujo de trabajo eficiente.

---

## 📌 Issues

Los *issues* (problemas) son una forma de reportar errores, proponer mejoras o discutir ideas relacionadas con un proyecto.

### ¿Cómo crear un Issue?

1. Ve al repositorio donde quieres crear el issue.
2. Haz clic en la pestaña **Issues**.
3. Haz clic en el botón **New Issue**.
4. Escribe un título claro y una descripción detallada del problema o sugerencia.
5. (Opcional) Asigna etiquetas, personas o hitos.
6. Haz clic en **Submit new issue**.

### ¿Para qué se usan?

- Reportar bugs (errores).
- Sugerir nuevas funcionalidades.
- Hacer preguntas o iniciar una discusión.
- Asignar tareas a miembros del equipo.

---

## 🔁 Pull Requests

Un *pull request* (solicitud de extracción) se utiliza para proponer cambios en el código. Permite revisar, comentar y fusionar cambios en la rama principal del repositorio.

### ¿Cómo crear un Pull Request?

1. Haz un *fork* (si no tienes acceso al repositorio original) o crea una nueva rama desde `main`.
2. Realiza los cambios en esa rama y haz un **commit**.
3. Sube tus cambios al repositorio (push).
4. Ve a la pestaña **Pull Requests** y haz clic en **New Pull Request**.
5. Compara la rama base (`main`) con tu rama con cambios.
6. Agrega un título y una descripción explicando los cambios realizados.
7. Haz clic en **Create Pull Request**.

### ¿Para qué se usan?

- Proponer nuevas características o correcciones.
- Revisar y comentar el código antes de fusionarlo.
- Asegurar calidad mediante revisiones por parte del equipo.

## 3. Gestión de Proyectos con GitHub Projects

### ¿Qué es?

Es una herramienta para visualizar y organizar tareas mediante tableros o tablas personalizadas.

### Tipos de proyectos

- Clásico (deprecated)
- Nuevo GitHub Projects (más flexible y automatizable)

### ¿Cómo crear un proyecto?

1. Ve a la pestaña **Projects**.
2. Haz clic en **New Project**.
3. Elige tipo de vista: tablero o tabla.
4. Nombra y configura el proyecto.

### Añadir elementos

- Agrega Issues, PRs o tarjetas libres.
- Usa columnas: *To do*, *In progress*, *Done*.
- Mueve tarjetas para reflejar el estado.

### Flujo sugerido

1. Crear un Issue.
2. Añadirlo al proyecto.
3. Moverlo entre columnas según el progreso.
4. Vincularlo con un PR.
5. Cerrar el Issue con el merge del PR.

### Mejores prácticas

- Actualiza el tablero regularmente.
- Usa etiquetas y prioridades.
- Divide tareas complejas.
- Usa automatizaciones.

---
