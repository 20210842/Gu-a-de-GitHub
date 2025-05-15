# Guía Básica de GitHub

Esta guía te ayudará a comprender dos funciones clave de GitHub: **Issues** , **Pull Requests** , **Gestion de proyectos con GitHub** y ------. Son herramientas esenciales para colaborar en proyectos, gestionar tareas y mantener un flujo de trabajo eficiente.

---

## 1. Issues

Los *issues* (problemas) son una forma de reportar errores, proponer mejoras o discutir ideas relacionadas con un proyecto.

### ¿Cómo crear un Issue?

1. Ve al repositorio donde quieres crear el issue.
   ![image](https://github.com/user-attachments/assets/0aa591b2-75d5-49af-aca2-1bc46c4a9d5a)

2. Haz clic en la pestaña **Issues**.
   ![image](https://github.com/user-attachments/assets/ce1dc2bf-f181-4179-8441-2193794090ce)

3. Haz clic en el botón **New Issue**.
   ![image](https://github.com/user-attachments/assets/ee9e763b-bc3e-4a87-b909-6df67fe8a8ba)

4. Escribe un título claro y una descripción detallada del problema o sugerencia.
   ![image](https://github.com/user-attachments/assets/8fbb539a-07c6-4b0d-8dc4-ced293cabd15)

15. Haz clic en **Create**.
    ![image](https://github.com/user-attachments/assets/306d31cb-6952-41d5-b149-562cd4b7af75)


### ¿Para qué se usan?

- Reportar bugs (errores).
- Sugerir nuevas funcionalidades.
- Hacer preguntas o iniciar una discusión.
- Asignar tareas a miembros del equipo.

---

## 2. Pull Requests

Un *pull request* (solicitud de extracción) se utiliza para proponer cambios en el código. Permite revisar, comentar y fusionar cambios en la rama principal del repositorio.

### ¿Cómo crear un Pull Request?

1. Haz un *fork* (si no tienes acceso al repositorio original) o crea una nueva rama desde `main`.
   ![image](https://github.com/user-attachments/assets/06a774e3-9fca-4af9-b295-b365c7617682)
   
   ![image](https://github.com/user-attachments/assets/3610c432-e422-40db-969f-b5bf3a0395ba)
   
   ![image](https://github.com/user-attachments/assets/fdaae334-9165-4e4f-9478-e74303ca2d71)

3. Realiza los cambios en esa rama y haz un **commit**.
   ![image](https://github.com/user-attachments/assets/828ec3ac-0dc7-461f-917d-0d860794ed60)

5. Sube tus cambios al repositorio (push).
6. Ve a la pestaña **Pull Requests** y haz clic en **New Pull Request**.
   ![image](https://github.com/user-attachments/assets/dba03997-8fe5-49f6-8ccf-36888606b6ed)

8. Compara la rama base (`main`) con tu rama con cambios.
9. Agrega un título y una descripción explicando los cambios realizados.
    ![image](https://github.com/user-attachments/assets/27163801-8b32-4041-9739-474430fab7f5)

11. Haz clic en **Create Pull Request**.
    ![image](https://github.com/user-attachments/assets/752ef89a-54d8-455b-b2c1-e1668a8b3719)


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
