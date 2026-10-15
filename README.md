# LECTA STEAM

Aplicación para preparar actividades de comprensión lectora: texto, configuración pedagógica y preguntas editables, con materiales para el alumnado y solucionario para el docente.

Este repositorio público reúne documentación, novedades y descargas. El código fuente se mantiene en privado.

## Estado del proyecto

Versión piloto: **0.1.0-piloto.6**, para **Windows x64**. El responsable del proyecto confirma que pasan todas las pruebas y que el nuevo paquete extraído funciona correctamente. Es una versión en evaluación y puede presentar incidencias.

## Descargar y empezar

**[Descargar LECTA STEAM 0.1.0-piloto.6 para Windows x64](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases/download/v0.1.0-piloto.6/LECTA-STEAM-0.1.0-piloto.6-win-x64-20261015-121949-cf45a464.zip)** · ZIP de aproximadamente 56 MB.

Consulta las [notas de esta versión](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases/tag/v0.1.0-piloto.6) o el [historial de versiones publicadas](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases).

1. Extrae el ZIP completo en una carpeta.
2. Abre `Iniciar-LECTA-STEAM.cmd`.
3. Utiliza la aplicación en la ventana del navegador que se abre.
4. Para cerrar, guarda los cambios y pulsa **Ctrl+C** en la consola.

El paquete incluye el entorno .NET necesario. Conserva la carpeta `app` completa. Los archivos automáticos de GitHub llamados **Source code** contienen la documentación de este repositorio, no el programa instalable ni su código fuente.

Consulta la [guía docente](GUIA-DOCENTE.txt) para las instrucciones completas.

## Funciones disponibles

- Descargar fichas digitales para responder en el navegador y conservar una copia con respuestas.
- Importar entregas en la actividad de origen y revisarlas junto al solucionario.
- Guardar observaciones por pregunta, comentario general y estado de revisión.
- Devolver fichas corregidas en HTML imprimible o PDF.

- Crear un glosario editable y mostrarlo opcionalmente en la ficha del alumnado y el PDF.
- Proponer términos con un chat de IA, revisar sus definiciones y seleccionar cuáles incorporar.
- Navegar por pestañas y plegar apartados para reducir la información visible.
- Abrir actividades por su título y utilizar el menú ⋮ para duplicar, exportar o crear variantes.
- Acceder a generación y revisión en IA, a los apoyos en Adaptaciones y a la impresión en Vista y PDF.
- Crear, guardar, buscar y duplicar actividades.
- Crear variantes independientes con apoyos de lectura.
- Adaptar textos con ayuda de un chat y comparar la propuesta antes de incorporarla.
- Revisar y sustituir preguntas individuales conservando su posición y metadatos.
- Configurar dificultad y distribución por procesos de comprensión.
- Añadir, editar, ordenar y eliminar preguntas, con respuestas esperadas, criterios, opciones y evidencias.
- Preparar instrucciones para un chat de IA y revisar sus propuestas antes de incorporarlas.
- Ajustar tamaño de letra, interlineado y separación de preguntas.
- Mostrar la lectura en párrafos numerados.
- Elegir de 0 a 10 líneas de respuesta por pregunta sin opciones.
- Añadir instrucciones para el alumnado antes de las preguntas.
- Revisar campos incompletos y evidencias textuales antes de imprimir.
- Previsualizar materiales del alumno y solucionario; obtener PDF mediante la impresión del navegador.
- Exportar e importar actividades mediante archivos `.lecta`.

## Uso local y generación asistida

La edición y el guardado funcionan localmente. LECTA STEAM no exige una clave API ni un servicio de IA de pago. La generación asistida consiste en copiar instrucciones a un chat externo y traer su respuesta para revisarla. El acceso a ese servicio depende de sus propias condiciones y límites.

Las actividades se guardan en `%LOCALAPPDATA%\LectaSteam\Data`. No se sincronizan automáticamente con otros equipos. Cierra la aplicación antes de copiar esa carpeta como respaldo.

Los archivos `.lecta` incluyen respuestas y notas docentes: están destinados al intercambio entre profesores. Para el alumnado, utiliza su vista, PDF o ficha digital.

Esta versión importa los formatos `.lecta` 1, 2, 3 y 4, y exporta en formato 4. Piloto.4 y las versiones anteriores no pueden importar los archivos nuevos: actualiza también el equipo receptor.

Esta versión añade una tabla para las entregas y conserva el material existente. Las migraciones pendientes se aplican al iniciar con una copia previa en `CopiasAntesDeActualizar` dentro de la carpeta de datos.

Las entregas y sus observaciones se guardan localmente y no se incluyen al exportar `.lecta`. Para conservarlas, respalda la carpeta de datos completa. Una ficha pertenece a la actividad exacta que la generó; las copias y variantes tienen otra identidad.

No hay envío automático a correo o Drive, ni calificación automática. El alumnado debe descargar su copia para conservar las respuestas.

## Evolución e incidencias

Consulta el [historial de cambios](CHANGELOG.md). Para comunicar un problema, indica la versión, los pasos para reproducirlo y el mensaje observado. No publiques actividades con datos personales, claves ni bases de datos en las incidencias del repositorio.

La publicación de documentación y descargas no convierte el código fuente en público ni concede por sí sola una licencia de código abierto.
