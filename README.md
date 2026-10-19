# Hama Beads Shop 🎨✨

Landing page de alta conversión para la venta del **Mega Pack de +1000 Patrones de Hama Beads en PDF + 3 Bonos de Regalo**, con oferta única en dólares (**$9.90 USD**).

Optimizada especialmente para campañas de **Meta Ads (Facebook e Instagram)** dirigidas a público hispanohablante en todo el mundo.

---

## 🚀 Características

- **Idioma:** Español neutro persuasivo de respuesta directa.
- **Oferta única:** Mega Pack completo por **$9.90 USD** (Pago único, sin suscripciones).
- **Incluye:**
  - +1000 patrones y plantillas en alta resolución (PDF).
  - 12 categorías temáticas organizadas (Animes, Pokémon, Videojuegos, Kawaii, Superhéroes, etc.).
  - **Bono 1:** Lista de Materiales y Proveedores Recomendados (Gratis).
  - **Bono 2:** Tabla de Colores y Combinaciones Exactas (Gratis).
  - **Bono 3:** Guía del Patrón a la Pieza Perfecta con técnicas de planchado (Gratis).
  - Acceso de por vida y futuras actualizaciones.
- **Meta Ads UTM Forwarder:** Script integrado que detecta automáticamente parámetros como `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`, `utm_term`, `fbclid` y los transmite a todos los botones de pago (`data-checkout`).
- **Barra fija móvil (Sticky Bar):** Aparece al hacer scroll en dispositivos móviles para maximizar la tasa de conversión.
- **Diseño ultra rápido y ligero:** Assets locales optimizados en WebP, sin dependencias pesadas.

---

## 🔗 Cómo cambiar tu enlace de Checkout

Todos los botones de compra utilizan enlaces con el atributo `data-checkout`. Para apuntar a tu propia pasarela de pago (Hotmart, Stripe, Lowify, Shopify, etc.), simplemente busca y reemplaza en `index.html`:

```html
href="https://pay.lowify.com.br/checkout.php?product_id=vJJWWt..."
```

Por el enlace de tu checkout con el producto de $9.90 USD.

---

## 📁 Estructura del Proyecto

```
hama-beads/
├── index.html         # Landing page completa en español
├── assets/            # Imágenes WebP optimizadas, fuentes y SVGs
├── README.md          # Documentación del proyecto
```

---

© 2026 **Hama Beads Shop**. Todos los derechos reservados.
