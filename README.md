# Citroën Aircross Max Híbrida — Vibras Motor

App (PWA) estilo Toyota para cotizar la **Citroën C3 Aircross Max Híbrida 2027** con código de referido Vibras Motor. Hecha para proponerle a **Automotores Comagro** (concesionario Citroën) el negocio de comisión por venta referida.

Sitio: https://haroldco45.github.io/citroen-aircross-max/

## Qué trae
- Precio desde $92.490.000* (promocional, crédito a mínimo 18 meses).
- "¿Cuál es su plan?": familia, carretera, finca y trocha, ciudad, con lo bueno y lo que debe saber.
- Fotos (Wikimedia Commons, CC BY-SA 4.0), ficha técnica y 3 videos de reseñas en Colombia.
- Simulador de cuota (tasa de ejemplo editable).
- Cotización con código de referido `VM-CIT-AAMMDD-NNNN` (hora Colombia): primero avisa a Harold por WhatsApp; luego, opcional, al concesionario.
- "Ya compré": registra la compra (asesor, pedido/factura) y le da al cliente el mensaje para que el asesor anote el código.
- PWA instalable, funciona sin conexión. Aviso de datos según Ley 1581 de 2012.

## Configurar
En `index.html`, bloque `CONFIG` al inicio del script:
- `harold.whatsapp`: 573117700431
- `concesionario.whatsapp`: 573245907205 (Comagro). Déjelo en `""` para quitar el segundo paso.
- `prefijo`: VM-CIT

## Publicar
1. Crear repo `citroen-aircross-max` en github.com/haroldco45.
2. Subir todo: `index.html`, `manifest.json`, `sw.js`, `og.jpg`, `README.md` y la carpeta `img/`.
3. Settings → Pages → Branch `main` / root.

Al cambiar archivos, sube la versión en `sw.js` (`aircross-max-v2`) para que los teléfonos tomen el cambio.

---
Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados
