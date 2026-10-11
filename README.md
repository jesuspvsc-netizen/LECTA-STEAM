# LECTA STEAM

Aplicación para preparar actividades de comprensión lectora: texto, configuración pedagógica y preguntas editables, con materiales para el alumnado y solucionario para el docente.

Este repositorio público reúne documentación, novedades y descargas. El código fuente se mantiene en privado.

## Estado del proyecto

Versión piloto: **0.1.0-piloto.1**, para **Windows x64**. El paquete se ha probado en el equipo de desarrollo; queda pendiente verificarlo en un segundo ordenador. Es una versión en evaluación y puede presentar incidencias.

## Descargar y empezar

Las versiones publicadas estarán disponibles en la sección **Releases** de este repositorio. Descarga el ZIP cuyo nombre comienza por `LECTA-STEAM-0.1.0-piloto.1-win-x64`.

1. Extrae el ZIP completo en una carpeta.
2. Abre `Iniciar-LECTA-STEAM.cmd`.
3. Utiliza la aplicación en la ventana del navegador que se abre.
4. Para cerrar, guarda los cambios y pulsa **Ctrl+C** en la consola.

El paquete incluye el entorno .NET necesario. Conserva la carpeta `app` completa. Los archivos automáticos de GitHub llamados **Source code** contienen la documentación de este repositorio, no el programa instalable ni su código fuente.

Consulta la [guía docente](GUIA-DOCENTE.txt) para las instrucciones completas.

## Funciones disponibles

- Crear, guardar, buscar y duplicar actividades.
- Configurar dificultad y distribución por procesos de comprensión.
- Añadir, editar, ordenar y eliminar preguntas, con respuestas esperadas, criterios, opciones y evidencias.
- Preparar instrucciones para un chat de IA y revisar sus propuestas antes de incorporarlas.
- Ajustar tamaño de letra, interlineado y separación de preguntas.
- Revisar campos incompletos antes de imprimir.
- Previsualizar materiales del alumno y solucionario; obtener PDF mediante la impresión del navegador.
- Exportar e importar actividades mediante archivos `.lecta`.

## Uso local y generación asistida

La edición y el guardado funcionan localmente. LECTA STEAM no exige una clave API ni un servicio de IA de pago. La generación asistida consiste en copiar instrucciones a un chat externo y traer su respuesta para revisarla. El acceso a ese servicio depende de sus propias condiciones y límites.

Las actividades se guardan en `%LOCALAPPDATA%\LectaSteam\Data`. No se sincronizan automáticamente con otros equipos. Cierra la aplicación antes de copiar esa carpeta como respaldo.

Los archivos `.lecta` incluyen respuestas y notas docentes: están destinados al intercambio entre profesores. Para el alumnado, utiliza su vista o su PDF.

## Evolución e incidencias

Consulta el [historial de cambios](CHANGELOG.md). Para comunicar un problema, indica la versión, los pasos para reproducirlo y el mensaje observado. No publiques actividades con datos personales, claves ni bases de datos en las incidencias del repositorio.

La publicación de documentación y descargas no convierte el código fuente en público ni concede por sí sola una licencia de código abierto.
