# VISOR CIUDADANO · Santiago

Visor web de revisión para localización y formulación de iniciativas ciudadanas en la comuna de Santiago. Incluye mapa Leaflet con fondo Esri, dibujo de puntos, líneas y polígonos, identificación de barrios y MATCH exploratorio con proyectos PDT.

## Publicación

Ruta prevista: https://phdgeografo.github.io/VISOR-CIUDADANO/ — requiere habilitar GitHub Pages desde Settings > Pages, rama main, carpeta /(root).

## Fuentes y trazabilidad

- Carpeta documental de referencia **PLATAFORMA MONITOREO**: https://drive.google.com/drive/folders/1yqBAUOnbRpvYHcZIerXXwysecAzIIrix
- Base temática pública auxiliar: pdt-proyectos-listado.json (proyectos PDT, sin datos personales de participantes).
- Original de la primera versión: versiones/index-inicial.html.
- Versión más completa adaptada de PHDGEOGRAFO/VISOR-INICIATIVAS-CIUDADANAS-VIC-.

## Seguridad y estado

**Versión demostrativa:** GitHub Pages no es una base de datos transaccional. No almacena de forma centralizada ni segura las propuestas enviadas por distintos ciudadanos. Ninguna contraseña embebida en JavaScript protege realmente el panel administrador. Los datos de identificación, teléfonos, direcciones o correos de participantes no deben subirse al repositorio ni a archivos GeoPackage públicos.

Falta implementar un backend privado con autenticación real, persistencia histórica de iniciativas, respaldo por temática y geometría en Google Drive, vínculo individual con los 307 registros espaciales PDT y validación institucional del MATCH. La matriz de proyectos y la capa geográfica no son necesariamente equivalentes registro a registro.
