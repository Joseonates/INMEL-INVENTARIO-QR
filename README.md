# Inventario QR — PWA Fase 1.1

Esta versión está preparada para probarse desde un celular sin Android Studio.

## Importante
La cámara requiere HTTPS. No funciona de forma fiable abriendo index.html como archivo local.

## Publicación rápida
Sube index.html, manifest.json y sw.js a un hosting HTTPS. GitHub Pages, Netlify o Cloudflare Pages son opciones válidas.

## Prueba
1. Abre la URL HTTPS en Chrome Android.
2. Concede permiso de cámara.
3. Pulsa Iniciar escáner.
4. Escanea Serial.
5. Escanea MAC.
6. Pulsa Guardar.
7. Instala desde Chrome con "Añadir a pantalla de inicio" si aparece.

El lector de códigos usa html5-qrcode desde CDN para esta prueba; por tanto, el primer arranque necesita Internet.
