MI GALAXIA - PRIMER PROTOTIPO

Contenido:
- Biblioteca local con importación PDF/EPUB.
- Vista de portadas y vista de lomos.
- Filtros de lectura.
- Datos de libros guardados en IndexedDB del navegador.
- Lector PDF mediante el visor integrado del navegador.
- Lector EPUB mediante epub.js (se descarga desde CDN en esta versión).
- Manifiesto e icono para instalación como PWA.
- Service worker para cachear los archivos de la aplicación.

IMPORTANTE:
1. Para instalar una PWA en Android, los archivos deben estar publicados en una dirección HTTPS (o localhost).
2. Este prototipo todavía no es un APK nativo.
3. Los archivos importados se guardan en el almacenamiento del navegador de ese dispositivo. No borres los datos del sitio si quieres conservarlos.
4. La primera versión usa epub.js desde un CDN; para garantizar lectura EPUB completamente offline, hay que incorporar esa biblioteca al paquete local en una siguiente compilación.
5. El progreso y el contador de lectura son iniciales; aún falta implementar paginación precisa, temporizador real, citas, metas y respaldo.
