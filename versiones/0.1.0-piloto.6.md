# LECTA STEAM 0.1.0-piloto.6

Publicada el 15 de octubre de 2026 como versión piloto para Windows x64. El docente confirma la compilación y el funcionamiento del paquete.

[Descargar ZIP](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases/download/v0.1.0-piloto.6/LECTA-STEAM-0.1.0-piloto.6-win-x64-20261015-121949-cf45a464.zip) · [Ver publicación](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases/tag/v0.1.0-piloto.6).

## Novedades

- Exportación de fichas digitales HTML que funcionan sin conexión y sin instalar LECTA STEAM en el equipo del alumno.
- Respuesta breve, respuesta abierta y elección múltiple.
- Descarga de una copia con respuestas y recuperación al volver a abrirla.
- Importación de entregas en la actividad de origen, con validación del contenido y detección de duplicados.
- Revisión docente junto al solucionario, observaciones por pregunta, comentario general y estado pendiente/revisada.
- Persistencia de entregas y revisiones en SQLite, con protección frente a sobrescrituras desde otra ventana.
- Descarga de la ficha corregida con respuestas y comentarios, imprimible en PDF.
- Guía del recorrido completo: preparar, responder, entregar, revisar y devolver.

## Límites de esta fase

No hay envío automático por correo o Drive, cuentas de alumno, calificación automática ni sincronización entre equipos.
El alumno debe descargar su copia para conservar las respuestas; no existe guardado automático.
La importación corresponde a la actividad exacta que generó la ficha. Una copia o variante tiene otra identidad.
El solucionario se conserva en la revisión tal como estaba al importar, y no se exporta oculto en los HTML del alumno.
Las observaciones escritas por el docente sí se incluyen íntegramente en la ficha corregida.

## Compatibilidad y actualización

Se mantiene el formato .lecta 4 y la importación de formatos 1 a 4.
Las entregas y anotaciones no se exportan en .lecta, no se duplican con las actividades y no forman parte del ZIP del programa.
La migración añade la tabla Entregas. El arranque guarda una copia antes de aplicar cambios pendientes en la base de datos.
Con la aplicación cerrada, conserva además una copia de toda la carpeta de datos antes de actualizar.

La versión portable guarda en `%LOCALAPPDATA%\LectaSteam\Data`. Visual Studio utiliza `LectaSteam.Web/Data`.
Extrae el ZIP en otra carpeta y abre `Iniciar-LECTA-STEAM.cmd`. No ejecutes dos versiones locales a la vez.

## Validación comunicada

El docente confirma el funcionamiento de las fichas digitales, la importación, la conservación de comentarios al cerrar y reabrir,
la devolución corregida y todas las pruebas. No se ha ejecutado .NET en el entorno remoto.

## Comprobación del ZIP antes de publicar

1. Generar el paquete con Crear-Portable.cmd.
2. Extraerlo en una carpeta nueva y abrir Iniciar-LECTA-STEAM.cmd.
3. Abrir una actividad y descargar una ficha digital. Rellenarla y descargar la copia con respuestas.
4. Importar esa copia en la misma actividad, añadir comentarios y guardar.
5. Cerrar y reabrir el programa; comprobar que la revisión se conserva.
6. Descargar la ficha corregida y comprobar su impresión en PDF.
7. Comunicar el nombre del ZIP y el SHA-256 generado.

## Paquete comprobado por el docente

Archivo:
`LECTA-STEAM-0.1.0-piloto.6-win-x64-20261015-121949-cf45a464.zip`

SHA-256 del empaquetado, coincidente con el digest del ZIP publicado por GitHub:

```text
9F5EACB1577F657F7DAC456263356BC96F1342039F60DCACC04C818E46579F10
```

Este valor corresponde a este ZIP concreto. La publicación es visible y está marcada como versión preliminar.
