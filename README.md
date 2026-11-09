# 🎙️ Loquendo Web Ecosystem

Sintetizador de voz Text-to-Speech (TTS) independiente desplegable como SPA (Single Page Application) sin necesidad de base de datos externa.

## 🚀 Características
- **Zero-Database Architecture:** Autenticación fluida utilizando únicamente Discord OAuth2 (`loquendo oauth`).
- **Natively Monetized:** Integrado con el bot `loquendo premium` mediante las suscripciones prémium integradas de Discord.
- **Full Social Embeds & Open Graph:** Diseñado para generar vistas previas ricas en redes sociales (Discord, Twitter, WhatsApp, Telegram, Facebook).
- **SEO Ready:** Incluye `sitemap.xml`, `sitemaps.xml`, `robots.txt` y metaetiquetas Open Graph completas.

## 📁 Archivos del Proyecto
- `index.html`: Aplicación principal TTS.
- `privacy.html`: Política de privacidad para el Discord Developer Portal.
- `terms.html`: Términos de servicio para el Discord Developer Portal.
- `favicon.svg`: Icono vectorial oficial.
- `banner.svg`: Banner para previsualización social (1200x630px Open Graph).
- `robots.txt` & `sitemap.xml` / `sitemaps.xml`: Archivos de rastreo de buscadores.

## ⚙️ Configuración rápida
1. Reemplaza `TU_CLIENT_ID_LOQUENDO_OAUTH` en `index.html` con la ID de tu aplicación en Discord Developer Portal.
2. Reemplaza `https://loquendo.on-html.duckdns.org/` en las metaetiquetas y sitemaps por tu dominio exacto.
