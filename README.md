# Demo educativa de QR / Quishing

Esta es una demostración para una charla de concienciación.

## Qué hace

- Simula una página que parece un documento compartido por WhatsApp.
- Tras pulsar "Ver documento", muestra información técnica que el navegador ya conoce.
- No solicita ni captura contraseñas.
- No solicita cámara, micrófono, geolocalización ni archivos.
- No envía los datos a un servidor.
- Es completamente estática y apta para GitHub Pages.

## Publicación

1. Crea un repositorio público en GitHub, por ejemplo `qr-quishing-demo`.
2. Sube `index.html` a la raíz del repositorio.
3. En **Settings → Pages**, selecciona **Deploy from a branch**.
4. Selecciona `main` y `/ (root)` y guarda.
5. GitHub publicará el sitio en una URL similar a:
   `https://TU_USUARIO.github.io/qr-quishing-demo/`
6. Genera un QR apuntando a esa URL.

Consulta la documentación oficial:
https://docs.github.com/es/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Nota

GitHub Pages es alojamiento estático. Por diseño, esta demo no registra IP ni otros datos en una base de datos propia.
