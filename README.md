# Luminoise: la luz extraíble

Ensayo visual sobre una instalación audiovisual y software a medida que investiga la imagen digital como depósito de luz material, extraíble y mutable.

## Contenido

- `index.html` — Documento principal (autónomo, sin dependencias externas, 1.7 MB)
- `og-image.png` — Imagen de preview para redes sociales (1200×630)
- `tesis-luminoise.pdf` — Versión PDF descargable (0.87 MB)

## Ver el proyecto

### Local
Abre `index.html` con doble clic en cualquier navegador. No requiere servidor ni conexión a internet.

### GitHub Pages
1. Sube el contenido de esta carpeta a un repositorio público
2. Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → Folder: `/ (root)`
3. En 1-2 minutos: `https://tuusuario.github.io/nombre-repo/`

### Otras opciones
- **Netlify Drop**: arrastra la carpeta a https://app.netlify.com/drop
- **Cloudflare Pages**: "Create a project" → "Upload assets" → arrastra la carpeta
- **surge.sh**: `npx surge` desde esta carpeta

## Nota técnica

El HTML es completamente autónomo:
- Fuentes embebidas (Courier Prime + Playfair Display, TTF base64)
- 5 imágenes en base64 (Láminas I–V)
- Sin scripts, sin CDN, sin peticiones de red
- CSS `@media print` para generar PDF fiel al diseño

## Créditos

Proyecto Luminoise · SISIFO® · 2026