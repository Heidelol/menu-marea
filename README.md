# Menú Marea — prototipo de menú digital

Prototipo de menú digital para restaurantes: catálogo con fotografía generada por IA, carrito de compra y envío de pedidos directo por WhatsApp (sin comisión de apps de delivery).

## Uso

Es un sitio estático de un solo archivo (`index.html`), sin dependencias ni build. Se puede abrir directamente en el navegador o desplegar en cualquier hosting estático (Vercel, Netlify, GitHub Pages).

## Personalización

- Edita el arreglo `MENU` dentro de `index.html` para cambiar platillos, precios y descripciones.
- Cambia `RESTAURANT_WA_NUMBER` por el número real de WhatsApp del restaurante (formato internacional, sin `+`).
- Las fotos están embebidas como imágenes base64 generadas por IA — reemplázalas por fotografía real del restaurante cuando esté disponible.
