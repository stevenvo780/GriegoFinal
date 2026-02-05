# Repository Guidelines

## Idioma de Trabajo
Este repositorio es un espacio de estudio de griego y la comunicación debe realizarse en español. Todas las respuestas, notas y documentación nueva deben redactarse en español.

## Estructura del Proyecto y Organización
Este repositorio es una base de conocimiento en Markdown para el estudio del griego clásico. El contenido se organiza por tema, no por módulos de código.

- `Clases/`: apuntes de clase y tablas de referencia.
- `Gramáticas/`: referencias gramaticales y método de estudio.
- `Libros de ejercicios/`: libros y textos base.
- `Ejercicios de traducción/`: traducciones con análisis.
- Archivos `.md` en la raíz: índices, glosarios y consolidaciones (ej. `Glosario.md`, `TraduccionCompleta.md`, `SolucionFinal.md`).

## Comandos de Desarrollo
No hay sistema de build ni pruebas automatizadas. El trabajo típico es editar archivos Markdown.

Comandos útiles:
- `rg "termino"`: búsqueda rápida en todo el contenido.
- `ls "Libros de ejercicios"`: listar fuentes de ejercicios.

## Estilo y Convenciones
Formato principal: Markdown.

- Indentación: 2 espacios para listas anidadas.
- Encabezados: estructura clara H1/H2; mantener títulos en español si el documento está en español.
- Nombres de archivos: descriptivos en español con guiones bajos (ej. `Clase_3_El_verbo_en_griego_antiguo.md`).
- Preferir párrafos breves y listas cortas para análisis y notas de traducción.

## Guía de Pruebas
No hay pruebas automatizadas. La validación se realiza por revisión entre pares y contraste con gramáticas y glosarios. Si se agregan scripts de verificación, deben documentarse aquí.

## Guía de Commits y Pull Requests
Los commits recientes usan resúmenes breves en español y modo imperativo (ej. "Reorganiza...", "Alinea..."). Mantén este patrón:

- Mensajes en presente e imperativo, < 72 caracteres.
- Mencionar el área afectada (ej. "Clases", "Gramáticas", "Glosario").

Los pull requests deben incluir:
- Resumen breve de cambios.
- Archivos o secciones tocadas.
- Si aplica, ejemplos antes/después o aclaraciones gramaticales.

## Instrucciones para Agentes
Este repositorio está optimizado para flujos de traducción asistidos por IA. Al agregar análisis nuevos, separa claramente: morfología, traducción y validación.
