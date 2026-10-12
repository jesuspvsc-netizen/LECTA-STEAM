# LECTA STEAM 0.1.0-piloto.3

Paquete piloto para Windows x64, publicado el 12 de octubre de 2026.

[Descargar el ZIP](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases/download/v0.1.0-piloto.3/LECTA-STEAM-0.1.0-piloto.3-win-x64-20261012-174927-456aaa2c.zip) · [Ver la publicación](https://github.com/jesuspvsc-netizen/LECTA-STEAM/releases/tag/v0.1.0-piloto.3).

## Novedades

- Párrafos numerados opcionales en la lectura del alumno y su PDF, sin modificar el texto original.
- Entre 0 y 10 líneas de respuesta por pregunta, aplicadas cuando no tiene opciones de respuesta.
- Instrucciones para el alumnado al crear y editar actividades, mostradas antes de las preguntas.
- Conservación de estos ajustes al guardar, duplicar, crear variantes y exportar/importar.
- Actualización de la base de datos con copia previa también en desarrollo.
- Guía docente actualizada.

## Compatibilidad y actualización

Las actividades existentes conservan tres líneas por pregunta y quedan sin instrucciones hasta que el docente las añada.

Esta versión importa archivos .lecta de formatos 1, 2 y 3, y exporta en formato 3. Para abrir los archivos nuevos en otro equipo, actualiza también su aplicación. Los archivos .lecta contienen soluciones y notas docentes; para el alumnado utiliza su vista o PDF.

Guarda y cierra la aplicación, conserva una copia de su carpeta de datos y extrae el ZIP nuevo en otra carpeta. Abre `Iniciar-LECTA-STEAM.cmd`; el paquete incluye .NET. No ejecutes dos versiones simultáneamente.

Los datos locales permanecen en `%LOCALAPPDATA%\LectaSteam\Data`. Esta actualización añade campos para líneas de respuesta e instrucciones. Antes de aplicar migraciones pendientes a una base existente, se guarda una copia en `CopiasAntesDeActualizar`, dentro de su carpeta de datos. No sustituye las copias de seguridad habituales.

## Validación comunicada

El responsable del proyecto confirma compilación correcta, todas las pruebas superadas y funcionamiento del paquete extraído, incluidos los ajustes nuevos y el PDF. Esta versión continúa en fase piloto.

## Archivo del programa

`LECTA-STEAM-0.1.0-piloto.3-win-x64-20261012-174927-456aaa2c.zip`

SHA-256 verificado contra el valor del empaquetado y el digest publicado por GitHub:

```text
8E6639BA8F6931315AC5FD167F9733290C38988A0314845CDD4829A58980F330
```

Este valor corresponde a este ZIP concreto.

## Uso local

LECTA STEAM no exige clave API. La generación asistida utiliza un chat externo mediante copia de instrucciones y respuestas, sujeto a las condiciones de ese servicio.

El siguiente bloque de desarrollo será la revisión del diseño y la organización de la interfaz.
