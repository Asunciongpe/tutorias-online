# Tutorías Escolares Online

Esta es una página web interactiva para la gestión y reserva de tutorías escolares en diferentes materias, diseñada para conectar estudiantes y tutores de forma sencilla.

## Funcionalidades

- **Selección de Materias:** El estudiante elige entre varias materias (Biología, Matemáticas, Química, Tecnología, Física, Francés, Inglés).
- **Tutores por Materia:** Cada materia muestra sólo los tutores disponibles para esa asignatura.
- **Reserva de Tutoría:** El estudiante selecciona materia, tutor, horario, duración y el monto a pagar (mínimo $40).
- **Panel del Tutor:** Cada tutor puede iniciar sesión para ver y aceptar las tutorías que le han solicitado.
- **Notificación Simulada:** Al reservar, la solicitud aparece en el panel del tutor correspondiente y se muestra el email al que se envió la notificación.

## Tutores y Materias

| Tutor                  | Correo electrónico                    | Materias                        | Contraseña   |
|------------------------|---------------------------------------|----------------------------------|--------------|
| Christian Roldan       | christian.roldan@anahuac.mx           | Biología, Matemáticas, Física, Química | 12345678     |
| Leonardo Cristino      | leonardo.cristino@anahuac.mx          | Matemáticas                     | 12345678     |
| Antonio Tovar          | antonio.tovar@anahuac.mx              | Matemáticas                     | 12345678     |
| Maria Vega             | maria.vega01@anahuac.mx               | Tecnología, Francés             | 12345678     |
| Valeria Nieves         | valeria.nieves@anahuac.mx             | Francés, Inglés                 | 12345678     |

## ¿Cómo usar?

1. **Descarga o clona este repositorio.**
2. Abre el archivo `index.html` en tu navegador.
3. Para probar el flujo de estudiante:
   - Haz clic en “¡Quiero registrarme!” y selecciona la opción estudiante.
   - Llena los campos, elige materia, tutor, fecha, duración y monto (mínimo $40).
   - Verás confirmación y a qué correo se envió la solicitud.
4. Para probar el panel de tutor:
   - Haz clic en “¡Quiero registrarme!” y selecciona la opción tutor.
   - Ingresa el correo y contraseña del tutor.
   - Visualiza y acepta las tutorías que te han asignado.

## Notas

- El sistema funciona completamente del lado del cliente (HTML, CSS y JavaScript puro).
- No se envían correos reales, pero la lógica muestra el correo al que se “notificaría”.
- Puedes modificar tutores, materias o contraseñas fácilmente editando el archivo `index.html`.

---

### Ejemplo de uso

1. Un estudiante reserva una tutoría de Biología con Christian Roldan.
2. Christian inicia sesión y ve la solicitud en su panel.
3. Christian puede aceptar la tutoría con un solo clic.

---

## Licencia

Este proyecto es de uso libre para fines educativos y demostrativos.
