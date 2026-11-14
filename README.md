# Refinamiento IA · Tokin

App web de Producto Digital de Tokin para las reuniones de refinamiento / Discovery con UX, IT y QA.

**App publicada:** https://gastonromano1998.github.io/refinamientoIA/

## Qué hace

- Graba la reunión (Webex, Meet o Teams desde el audio de la compu, o presencial con micrófono) y la transcribe con Groq Whisper.
- Identifica quién habla: tu voz por el micrófono y, con el módulo **Voces**, a cada persona que registró su prueba de voz.
- Genera historias de usuario con el esqueleto de Tokin (13 secciones, RN-XX, CA en Gherkin, checklist de calidad).
- Abre cada historia en sub-historias por equipo: UX, IT Back, IT Front y Admin.
- Exporta a Jira (CSV con historias y sub-tareas), Markdown y copia rápida por historia.
- Guarda las sesiones y las voces en Firebase Realtime Database.

## Estructura

Todo está en un solo archivo: `index.html`.
