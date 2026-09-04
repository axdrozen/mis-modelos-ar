# Pretty sourdough loaf · WebAR

Este sitio publica el modelo GLB y usa un marcador basado en el mismo código QR.

## Flujo de uso

1. Escanear el QR con la cámara del teléfono.
2. Abrir la página segura de GitHub Pages.
3. Pulsar **Activar cámara** y aceptar el permiso de cámara del navegador.
4. Apuntar al QR impreso: el modelo aparece anclado sobre el marcador.

La vista `viewer.html` funciona como respaldo para explorar el GLB en 3D y, cuando el teléfono lo permite, abrir sus modos de AR del navegador.

## Compatibilidad

No requiere instalar una aplicación adicional. La experiencia depende de que el navegador permita cámara/WebGL y del soporte de AR del teléfono. El repositorio debe ser público para que el QR funcione para cualquier persona.

## Créditos técnicos

- [AR.js](https://ar-js-org.github.io/AR.js-Docs/marker-based/) para el seguimiento del marcador.
- [A-Frame](https://aframe.io/) para renderizar el modelo GLB.
- [model-viewer](https://modelviewer.dev/docs/index.html) para la vista 3D de respaldo.
