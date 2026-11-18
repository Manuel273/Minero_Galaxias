MINERO: 10 GALAXIAS — WEB

Contenido para publicar: index.html, sw.js, manifest.webmanifest, icon.svg.

Para probar localmente, usa un servidor web (Service Worker requiere HTTPS o localhost).
Para publicar gratis, GitHub Pages es una opción: crea un repositorio, sube los 4 archivos a la raíz y activa Settings > Pages > Deploy from branch > main / root.

Después abre la URL Pages. La primera visita necesita Internet; luego queda disponible offline.
Las actualizaciones se buscan al abrir y cada 5 minutos si está online. Si se instala, el navegador puede pedir instalar/actualizar la app. El progreso local se conserva porque el código de juego mantiene su localStorage SAVE_KEY.
