# Comparativo Tabletas Rugged — DYMMSA

Presentación web (18 diapositivas) con el comparativo técnico y de costos de tabletas rugged empresariales.

## Estructura

- `index.html` — la presentación (diseño exportado de Claude Design)
- `deck-stage.js` / `support.js` — runtime del deck (navegación con teclado ←/→, escalado automático, impresión a PDF)
- `assets/` — imágenes de los modelos y logo

Es un sitio 100% estático: no requiere build ni dependencias.

## Ver localmente

```bash
npx serve .
```

## Deploy en Vercel

Importa el repositorio en Vercel y despliega con la configuración por defecto (framework preset: **Other**, sin build command, output directory: raíz). No se necesita `vercel.json`.
