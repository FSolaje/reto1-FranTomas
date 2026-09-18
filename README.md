# Reto 2: De tu máquina a GitHub

Este repositorio contiene el desarrollo y las evidencias correspondientes al **Reto 2**, enfocado en dar el salto del entorno local a la nube mediante la sincronización de un repositorio Git con **GitHub**.

## 📌 ¿Qué se hace en esta práctica?

* **Conexión con GitHub:** Creación de un repositorio remoto vacío y enlace con el entorno local utilizando autenticación por token (en LliureX/Linux) o *Git Credential Manager* (en Windows).
* **Sincronización de historiales:** Subida del repositorio local al remoto conservando todo el historial de commits mediante `git push -u origin main`.
* **Prueba de flujo bidireccional:** Simulación del viaje de vuelta (`git fetch` y `git pull`) editando archivos directamente desde la plataforma web de GitHub.
* **Extensiones opcionales:**
  * Despliegue de la página web utilizando **GitHub Pages**.
  * Configuración de acceso seguro mediante **claves SSH** (incluyendo adaptación al puerto 443 si es necesario).
