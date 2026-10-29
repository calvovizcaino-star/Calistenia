# Albaranes de Butano

App web para registrar manualmente albaranes, consultar los pendientes de pago y pasar albaranes a pagados.

## Archivos que hay que subir a GitHub

Sube **todo el contenido de esta carpeta**, manteniendo esta estructura:

- `index.html` — aplicación.
- `manifest.json` — configuración para instalar como app web.
- `service-worker.js` — caché básica para que la app cargue mejor y pueda abrirse sin conexión después de la primera visita.
- `icon-192.png` y `icon-512.png` — iconos de la app.

## Publicarla con GitHub Pages

1. Abre el repositorio en GitHub.
2. Sube o reemplaza `index.html`, `manifest.json` y `service-worker.js` en la raíz del repositorio.
3. Sube la carpeta `icons` con los dos PNG dentro.
4. En **Settings → Pages**, configura la publicación desde la rama `main` y la carpeta `/ (root)`.
5. Abre la dirección de GitHub Pages en Safari.
6. En el iPhone, pulsa **Compartir → Añadir a pantalla de inicio**.

## Importante sobre los datos

Los albaranes se guardan localmente en el navegador de ese iPhone. No se sincronizan con otros dispositivos ni se guardan en GitHub. Evita borrar los datos de Safari y exporta o anota los datos importantes como copia de seguridad. El service worker guarda archivos de la app, no los registros de albaranes.
