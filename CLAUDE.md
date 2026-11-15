# CLAUDE.md

HTML estático, un `index.html` autocontenido por carpeta (Tailwind CDN + Lucide 0.344.0 vía unpkg). Sin build.

- Los datos de la clínica (dirección, teléfono +34 653 48 78 25, email, horario, especialistas Adrián Quiles y Alejandra Oliván Pascual) están repetidos en las 5 páginas: si cambias uno, cámbialo en todas.
- El horario también está en el JS de la opción 3 (indicador de abierto/cerrado) y de la opción 5 (asistente y semana).
- Los formularios no envían nada a ningún servidor: abren WhatsApp con el texto ya preparado.
