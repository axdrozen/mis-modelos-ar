# Modelos 3D · WebAR

Este sitio publica modelos GLB. El QR abre la experiencia y selecciona el modelo; el seguimiento se realiza con un cubo físico reutilizable.

## Seguimiento del cubo

Cada cara usa una etiqueta AprilTag 36h11 distinta. La página transforma las caras visibles a un centro rígido común, combina sus poses y aplica filtrado temporal para reducir saltos al girar el cubo.

La plantilla imprimible y las instrucciones están en la carpeta `Cubo AR reutilizable` del escritorio. El QR no cambia cuando se publican modelos nuevos.

## Flujo de uso

1. Escanear el QR con la cámara del teléfono.
2. Pulsar **Activar cámara** y aceptar el permiso del navegador.
3. Apuntar al cubo AprilTag armado con la plantilla nueva.
4. Mantener dos caras visibles cuando sea posible y girar lentamente.

No requiere instalar una aplicación adicional, pero sí un navegador con cámara, WebGL y WebAssembly. La prueba final debe hacerse en el iPhone o Android real que se vaya a utilizar.

La vista `viewer.html` queda como respaldo para explorar el GLB en 3D.

## Créditos técnicos

- [AprilTag](https://github.com/AprilRobotics/apriltag) y su compilación WebAssembly para identificar las caras.
- [Three.js](https://threejs.org/) y `GLTFLoader` para renderizar el modelo GLB.
- [model-viewer](https://modelviewer.dev/docs/index.html) para la vista 3D de respaldo.
