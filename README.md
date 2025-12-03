# ATLACATL SGT (Sistema de Gestión de Tareas)

![Estado](https://img.shields.io/badge/Estado-Completado-success) ![Versión](https://img.shields.io/badge/Versión-1.0-blue) ![PHP](https://img.shields.io/badge/PHP-8.3-777BB4) ![MySQL](https://img.shields.io/badge/MySQL-Relacional-4479A1)

**Atlacatl SGT** es un sistema web académico desarrollado para el **Instituto Nacional de Antiguo Cuscatlán (INAC)**. Centraliza la gestión de tareas, entregas y calificaciones del Tercer Año de Bachillerato Técnico Vocacional en Desarrollo de Software, ofreciendo una alternativa ligera y personalizada a plataformas genéricas.

## STACK TECNOLÓGICO

| Categoría     | Tecnología        | Versión |
| :------------ | :---------------- | :------ |
| Backend       | PHP               | 8.3     |
| Base de Datos | MySQL             | N/A     |
| Frontend      | HTML5 / CSS3 / JS | ES2023  |
| Framework CSS | Bootstrap         | 5.6     |
| Entorno Local | XAMPP             | 3.3.0   |
| IDE           | VS Code           | 1.90.2  |

## FUNCIONALIDADES

### Módulo Docente

-   **CRUD de tareas** con archivos adjuntos.
-   **Calificación de entregas** con precisión decimal.
-   **Gestión de usuarios** (perfiles estudiantiles).
-   **Monitoreo de estado** de entregas por estudiante.

### Módulo Estudiante

-   **Entrega y reemplazo** de archivos (PDF, DOCX, IMG).
-   **Gestión de envíos** antes de la fecha límite.
-   **Dashboard** con tareas y notas.

## CAPTURAS DE PANTALLA

|          Login Alumno          |            Panel de Tareas             |
| :----------------------------: | :------------------------------------: |
| ![Login](img/login_screen.png) | ![Dashboard](img/dashboard_screen.png) |

## INSTALACIÓN

1. **Clonar el repositorio**

    ```bash
    git clone https://github.com/ernestolindo/atlacatl-sgt.git
    ```

2. **Base de datos**

    - Crear base en MySQL.
    - Importar `/database/script.sql`.

3. **Configurar conexión**

    - Editar `Clases/Database.php` con tus credenciales.

4. **Ejecución**

    - Servir desde `htdocs` (XAMPP).

## DOCUMENTACIÓN

Documentos completos disponibles en `/docs`:

-   Manual de Usuario
-   Manual de Instalación
-   Análisis y Diseño del Sistema

## EQUIPO DE DESARROLLO

-   **Ernesto Lindo** – Jefe de Equipo & Full Stack
-   **Ángel Araujo** – Backend & Database
-   **Ezequiel Pineda** – Frontend & UI/UX
-   **Héctor Medrano** – QA & Testing
-   **Víctor Benítez** – Documentación & Soporte

---

© 2024 Atlacatl SGT. Proyecto académico sin fines comerciales.
