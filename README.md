# Aire de Babia — Web Oficial

Sitio web estático para **Aire de Babia**, tres casas rurales de piedra en Piedrafita de Babia (Cabrillanes), León. Diseñado y desarrollado desde cero con HTML, CSS y JavaScript puro, sin frameworks ni dependencias externas.

🌐 **[airedebabia.es](https://www.airedebabia.es)** · 📸 **[@airedebabia](https://www.instagram.com/airedebabia/)**

---

## Páginas

| Archivo | Descripción |
|---|---|
| `index.html` | Página principal — casas, galería, contacto, FAQ |
| `actividades.html` | Actividades en la comarca de Babia |
| `404.html` | Página de error personalizada |

---

## Características

- **Bilingüe ES / EN** — toggle con persistencia en `localStorage`
- **Galería con lightbox** — 4 álbumes (Casa I, II, III, Exterior)
- **Tabs interactivos** — navegación entre las 3 casas
- **Formulario de contacto** — integrado con Formspree
- **WhatsApp popup** — dos números, botón flotante
- **Banner de cookies** — conforme a RGPD
- **Open Graph + SEO** — meta tags, `robots.txt`, `sitemap.xml`
- **Página 404 personalizada**
- **Totalmente responsive** — mobile first

---

## Stack

- HTML5 · CSS3 · JavaScript (vanilla)
- [Google Fonts](https://fonts.google.com/) — Playfair Display + Lato
- [Font Awesome 6.5](https://fontawesome.com/) — iconografía
- [Formspree](https://formspree.io/) — formulario de contacto

---

## Estructura

```
babiaa/
├── index.html
├── actividades.html
├── 404.html
├── favicon.svg
├── robots.txt
├── sitemap.xml
├── .htaccess
└── img/
    ├── casas/          # Fotos de las casas y patios
    ├── naturaleza/     # Paisajes y fauna de Babia
    └── actividades/    # Imágenes de actividades
```

---

## Despliegue

Alojado en **IONOS** con dominio personalizado `airedebabia.es`.  
El archivo `.htaccess` redirige los errores 404 a la página personalizada.

Para actualizar: subir los archivos modificados vía FTP al directorio raíz `/`.

---

## Desarrollo

Diseño y desarrollo — [Daniel Corpas](https://www.linkedin.com/in/daniel-corpas/)
