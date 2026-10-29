# Guías visuales — Weaves

Índice público de las guías visuales de cliente. Cada guía es el artefacto de aprobación
visual: paleta con valores reales, tipografías, formas y componentes renderizados.

## Publicación

- Sitio: https://weavesdv.github.io/guias/
- Rama: `main` (raíz del repo), sin build en CI: aquí vive el **dist ya compilado**.
- `.nojekyll` presente para que Pages no procese los assets con Jekyll.

## Estructura

```
index.html            hub de guías
404.html              fallback SPA (GitHub Pages no reescribe rutas)
divine-light/         Divine Light — Zuzel Amelia
  index.html          shell generada por Vite (base /guias/divine-light/)
  assets/             JS + CSS compilados
  paleta/index.html   guía de paleta v2 (calipso) — HTML standalone + DESIGN.md y tokens
```

## Guía Divine Light

### Paleta v2 (calipso) — 29-oct-2026

- Fuente de los valores: `lorieladd.com/40-days` (tokens leídos de su CSS). Independiente de la propuesta de
  diseño pendiente.
- Página: `/guias/divine-light/paleta/` — HTML standalone, sin build. Incluye `DESIGN.md` (normativo),
  `tokens.json` (DTCG) y `tailwind.theme.json`.
- Calipso `#70A3B2` como acento principal, papel de página `#F6F1EB` y rosa `#DAA79F` como segunda nota.

### Biblioteca de componentes (paleta v2)

- Build v0.7 (29-oct-2026): reconstruida con los tokens de la paleta v2 — papel `#F6F1EB`, calipso `#70A3B2`
  (`--brand-gold` y `--brand-cool`), calipso profundo `#4E727C` (`--brand-spirit`), rosa `#DAA79F`
  (`--brand-rose`), taupe `#AB9D8B` (`--brand-deep`).
- Fuente: `weaves-course-platform` (repo de cliente en labsryzen), `frontend/src/index.css` +
  `pages/ComponentLibrary.tsx`.
- Build: `npx vite build --base=/guias/divine-light/ --outDir dist-guias`; el `index.html` publicado es el del
  build con el script de redirección a `/componentes` añadido.
- Vista publicada: `/guias/divine-light/componentes` (la raíz redirige ahí).

## Añadir una guía nueva

1. Compilar con `--base=/guias/<slug>/` y `basename` equivalente.
2. Copiar el `dist/` a `<slug>/`.
3. Añadir la tarjeta en `index.html` y actualizar el fallback de `404.html` si cambia el mapa de rutas.
