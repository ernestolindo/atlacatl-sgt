# Atlacatl SGT (Sistema de Gestión de Tareas)

![Estado del Proyecto](https://img.shields.io/badge/Estado-Finalizado-success) ![Versión](https://img.shields.io/badge/Versión-1.0-blue)

[cite_start]**Atlacatl SGT** es una plataforma web de gestión de tareas diseñada para modernizar y optimizar el proceso educativo del **Instituto Nacional de Antiguo Cuscatlán (INAC)**[cite: 14, 39]. [cite_start]Este sistema nace como una alternativa personalizada, minimalista y eficiente a Google Classroom, enfocada específicamente en las necesidades del Tercer Año de Bachillerato Técnico Vocacional en Desarrollo de Software[cite: 17, 22].

## 📋 Características Principales

[cite_start]El sistema es una solución bilateral que conecta a docentes y estudiantes en un entorno intuitivo[cite: 31].

### 👨‍🏫 Para Docentes

-   [cite_start]**Gestión de Tareas:** Crear, editar y eliminar asignaciones con archivos adjuntos[cite: 32, 33].
-   [cite_start]**Calificaciones:** Panel de control para visualizar entregas y asignar notas (0-10 con decimales)[cite: 34, 68].
-   [cite_start]**Gestión de Estudiantes:** Administración completa (CRUD) de los perfiles estudiantiles[cite: 69].
-   [cite_start]**Panel de Control:** Visualización del estado de entrega de cada alumno[cite: 93].

### 👨‍🎓 Para Estudiantes

-   [cite_start]**Entregas:** Subida de archivos (PDF, Word, imágenes, etc.) para cada asignación[cite: 35, 64].
-   [cite_start]**Gestión de Entregas:** Posibilidad de cancelar y reenviar tareas antes de la fecha límite[cite: 65].
-   [cite_start]**Visualización:** Acceso claro a detalles de tareas, fechas límite y calificaciones[cite: 48].
-   [cite_start]**Seguridad:** Registro único con NIE y gestión de contraseña personal[cite: 61, 63].

## 🛠️ Stack Tecnológico

[cite_start]El proyecto fue desarrollado utilizando las siguientes tecnologías[cite: 369]:

-   [cite_start]**Lenguaje Backend:** PHP 8.3 [cite: 388]
-   [cite_start]**Base de Datos:** MySQL (Relacional) [cite: 408]
-   [cite_start]**Frontend:** HTML5, CSS3, JavaScript (ECMAScript 2023) [cite: 370, 397]
-   [cite_start]**Framework CSS:** Bootstrap 5.6 [cite: 384]
-   [cite_start]**Entorno de Desarrollo:** XAMPP 3.3.0 & VS Code [cite: 400, 403]

## 🚀 Instalación y Despliegue

[cite_start]Esta guía cubre el despliegue en un hosting gratuito (basado en InfinityFree) como se detalla en la documentación oficial del proyecto[cite: 424].

### Prerrequisitos

-   [cite_start]Cliente FTP (FileZilla recomendado)[cite: 420].
-   [cite_start]Cuenta de hosting con soporte PHP y MySQL[cite: 448].

### Pasos de Instalación

1.  **Configuración de la Base de Datos:**

    -   [cite_start]Crea una nueva base de datos MySQL desde el panel de control de tu hosting[cite: 498].
    -   [cite_start]Accede a **phpMyAdmin** e importa el archivo `.sql` de la base de datos local[cite: 503].

2.  **Carga de Archivos:**

    -   [cite_start]Conéctate a tu servidor vía FTP (Host, Usuario, Contraseña, Puerto 21)[cite: 484].
    -   [cite_start]Sube todo el contenido de la carpeta del proyecto a la carpeta pública `htdocs` del servidor remoto[cite: 491, 493].

3.  **Configuración de Conexión:**
    -   Edita el archivo `Database.php` (puede estar en la carpeta `Clases` o raíz).
    -   Actualiza las credenciales con los datos de tu hosting (diferentes a los locales):
    ```php
    private $dbhost = 'sql308.infinityfree.com'; // Ejemplo
    private $dbname = 'tu_nombre_de_base_de_datos';
    private $dbuser = 'tu_usuario';
    private $dbpass = 'tu_contraseña';
    ```
    -   Guarda los cambios y sube el archivo actualizado[cite: 506, 509].

## 👤 Credenciales de Acceso (Demo)

[cite_start]Para pruebas con la cuenta docente preconfigurada[cite: 177]:

-   **Correo:** `estrada.aleman@clases.edu.sv`
-   **Contraseña:** `INAC2024`

> [cite_start]**Nota:** Se recomienda cambiar estas credenciales inmediatamente desde el menú "Ajustes"[cite: 178].

## ✒️ Autores

[cite_start]Proyecto desarrollado por el equipo de estudiantes del INAC [cite: 6-10]:

-   [cite_start]**David Ernesto Lindo Argueta** (Jefe de equipo) [cite: 149]
-   **Ángel Josué Araujo Melara**
-   **Dagoberto Ezequiel Pineda Castillo**
-   **Héctor Alejandro Medrano Ceballos**
-   **Víctor Guillermo Benítez Montoya**

---

© 2024 Atlacatl SGT. [cite_start]Instituto Nacional de Antiguo Cuscatlán. [cite: 202]
