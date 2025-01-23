## Requisitos para Contribuir

1. **Pruebas:** Para contribuir tienes que asegrartete de incluir pruebas unitarias o funcionales cuando agregues nuevas funcionalidades.
2. **Documentación:**
    - Actualiza el archivo `README.md` con un resumen de los cambios o las nuevas funciones que implementes.
    - Explica en detalle las nuevas funcionalidades en `docs/features.md`. Incluye descripciones claras, ejemplos de uso, capturas de pantalla (si aplica) y cualquier configuración adicional que sea necesaria.
    - Si hiciste cambios en la base de datos, documenta esas modificaciones en `docs/database_documentation.md`.
    - Para nuevos comandos de consola o APIs, agrega ejemplos de cómo usarlos en la documentación.

## Pautas de Desarrollo

1. **Nuevas Funcionalidades:**

    - Describe los detalles en `docs/features.md`.
    - Agrega pruebas correspondientes en el directorio `tests`.
    - Explica cómo usar la nueva funcionalidad en el `README.md`.

2. **Modificaciones en la Base de Datos:**

    - Crea un archivo de migración siguiendo el formato estándar de Laravel.
    - En `database_documentation.md`, especifica:
        - La tabla afectada.
        - Los cambios realizados en las columnas.
        - La razón del cambio.

3. **Corrección de Errores:**

    - Describe el error solucionado en `docs/changelog.md`.
    - Incluye pruebas para demostrar que el error fue corregido.

4. **Estilo y Formato:**
    - Antes de enviar un pull request, utiliza herramientas como `PHP-CS-Fixer` o `Larastan` para asegurarte de que el código esté bien formateado y cumpla con los estándares de calidad.

## Flujo de Trabajo

1. **Fork y Clonación:**

    - Realiza un fork del repositorio y clona tu versión localmente.

    ```bash
    git clone https://github.com/tu-usuario-papu/code-snippet-platform.git
    ```

2. **Crea una Rama Nueva:**

    - Usa nombres descriptivos para las ramas.

    ```bash
    git checkout -b feature/nueva-funcionalidad
    ```

3. **Realiza Cambios y Pruebas:**

    - Desarrolla tu código y asegúrate de que las pruebas existentes y nuevas pasen correctamente.

4. **Confirma tus Cambios:**

    - Escribe mensajes de commit claros y concisos.

    ```bash
    git commit -m "feat: agrega funcionalidad para gestionar usuarios"
    ```

5. **Push y Pull Request:**

    - Sube tus cambios a tu repositorio y crea un pull request en el repositorio principal.

    ```bash
    git push origin feature/nueva-funcionalidad
    ```

6. **Revisión del Código:**
    - Responde a los comentarios y realiza los cambios necesarios.

## Documentos Importantes

-   `README.md`: Documentación general del proyecto.
-   `features.md`: Detalles de las funcionalidades del proyecto.
-   `changelog.md`: Registro de cambios del proyecto.
-   `database_documentation.md`: Descripción detallada de la estructura de la base de datos.
-   `CONTRIBUTING.md`: Guía detallada para contribuir al proyecto.

## Buenas Prácticas

-   Asegúrate de que el código sea reutilizable y legible.
-   Comenta partes complejas del código para facilitar su comprensión.
-   Realiza pruebas exhaustivas antes de enviar cualquier cambio.

Gracias por contribuir a este proyecto. ¡Tu esfuerzo es apreciado!
