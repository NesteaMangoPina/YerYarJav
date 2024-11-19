# Descripción de la tarea: Formulario para registrar entrenamientos

Se ha creado un formulario en HTML para que los usuarios de un centro deportivo puedan registrar los entrenamientos realizados.

## Características principales
- **Método de envío:** El formulario utiliza `POST` o `GET` hacia una URL de `webhook.site`.
- **Campo oculto:** Incluye el nombre y apellidos del usuario para identificar el envío.
- **Agrupación:** Los campos están organizados en:
  - **Datos usuario:** Información personal como DNI, nombre, contraseña, teléfono y correo.
  - **Datos entrenamiento:** Fecha, imágenes del entrenamiento y rutina en PDF.
  - **Rendimiento:** Valoración del esfuerzo, agua consumida y tipo de entrenamiento.
- **Validaciones:**
  - Formatos específicos para DNI, correo, teléfono y fechas (limitadas a 2024).
  - Campos obligatorios marcados con `(*)`.
- **Carga de archivos:** Permite subir imágenes en formato JPG y rutinas en formato PDF.
- **Elementos interactivos:** Controles deslizantes y listas desplegables.
- **Botones:** Incluye opciones para enviar y restablecer los datos del formulario.


