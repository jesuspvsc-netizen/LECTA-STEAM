# Historial de cambios

## 0.1.0-piloto.6 — 15 de octubre de 2026

- Fichas digitales HTML para responder y descargar una copia con respuestas.
- Importación de entregas en la actividad de origen y detección de duplicados.
- Revisión docente con observaciones por pregunta, comentario general y estado pendiente/revisada.
- Conservación de entregas y revisiones en SQLite.
- Devolución de fichas corregidas en HTML imprimible o PDF.
- Migración para la tabla Entregas y guía docente del recorrido completo.

El responsable confirma todas las pruebas y el funcionamiento del paquete en Windows.
El digest SHA-256 publicado por GitHub coincide con el comunicado durante el empaquetado.

[Notas y SHA-256](versiones/0.1.0-piloto.6.md).

## 0.1.0-piloto.5 — 14 de octubre de 2026

- Glosario manual en Adaptaciones: términos, definiciones, orden y eliminación.
- Visualización opcional después de la lectura en la ficha del alumnado y su PDF.
- Propuestas de glosario con IA mediante chat externo, con revisión y selección docente.
- Validación de estructura, duplicados, límites y cambios de contexto antes de incorporar.
- Glosarios independientes al duplicar, crear variantes e importar.
- Importación de formatos .lecta 1 a 4 y exportación en formato 4.
- Migración para la tabla del glosario y guía docente actualizada.

El responsable confirma todas las pruebas y el funcionamiento del paquete en Windows.
El SHA-256 publicado por GitHub coincide con el generado durante el empaquetado.

[Notas y SHA-256](versiones/0.1.0-piloto.5.md).

## 0.1.0-piloto.4 — 13 de octubre de 2026

- Pestañas en creación y edición; apartados plegables.
- Menú ⋮ en Mis actividades y apertura por el título.
- Accesos entre IA, adaptaciones, revisión de preguntas y PDF.
- Repaso de colores, controles, espaciado y navegación en ventanas estrechas.
- Sin nuevas migraciones respecto a piloto.3.

El responsable confirma compilación, pruebas y funcionamiento del paquete extraído. El SHA-256 del ZIP publicado por GitHub coincide con el del empaquetado.

[Notas y SHA-256](versiones/0.1.0-piloto.4.md).

## 0.1.0-piloto.3 — 12 de octubre de 2026

- Párrafos numerados opcionales en la vista del alumno y su PDF.
- Entre 0 y 10 líneas de respuesta por pregunta sin opciones.
- Instrucciones para el alumnado, disponibles al crear y editar actividades.
- Persistencia de los ajustes al guardar, duplicar, crear variantes y compartir.
- Importación de archivos .lecta de formatos 1, 2 y 3; exportación en formato 3.
- Migraciones para los nuevos campos, con copia previa también en desarrollo.
- Guía docente actualizada.

El responsable confirma todas las pruebas superadas y el funcionamiento del paquete extraído.
El SHA-256 publicado por GitHub coincide con el generado durante el empaquetado.

[Notas y SHA-256](versiones/0.1.0-piloto.3.md).

## 0.1.0-piloto.2 — 12 de octubre de 2026

- Inicio en español con ayuda y accesos para docentes.
- Variantes independientes con nombre y apoyos de lectura.
- Adaptación asistida del texto, con comparación previa e incorporación explícita.
- Revisión asistida y sustitución de preguntas individuales sin aumentar su número.
- Conservación de posición, proceso, formato, dificultad y puntuación al sustituir.
- Avisos de propuestas pendientes y de evidencias que ya no aparecen en el texto.
- Guía docente actualizada.

El responsable del proyecto confirma todas las pruebas correctas y el funcionamiento
del nuevo paquete extraído. No se añaden migraciones de base de datos.

[Notas y SHA-256](versiones/0.1.0-piloto.2.md).

## 0.1.0-piloto.1 — 11 de octubre de 2026

Primera versión piloto preparada como paquete local para Windows x64.

- Creación, edición, guardado, recuperación y duplicado de actividades.
- Configuración pedagógica y distribución de preguntas por procesos de comprensión.
- Gestión de preguntas, opciones y evidencias; reordenación y recuperación de la última pregunta eliminada antes de guardar.
- Generación asistida mediante intercambio de instrucciones y respuestas con un chat externo, con validación y revisión de propuestas.
- Guardado sin salir del editor y aviso al abandonar cambios pendientes.
- Edición compacta de preguntas y controles para expandirlas.
- Ajustes de lectura: letra, interlineado y separación.
- Vistas del alumno y solucionario, revisión previa e impresión a PDF.
- Búsqueda y filtros de actividades; intercambio mediante `.lecta`.
- Paquete con entorno .NET incluido, inicio local y apertura del navegador.
- Datos locales separados de la carpeta del programa.

### Verificación comunicada

El responsable del proyecto confirma compilación correcta y funcionamiento del paquete extraído en su equipo, incluido el guardado y la recuperación de actividades. El 11 de octubre de 2026 confirma también el funcionamiento en un segundo ordenador Windows x64. Esta versión se distribuye como piloto, no como versión estable.
