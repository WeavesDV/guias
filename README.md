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
```

## Guía Divine Light

- Fuente: `weaves-course-platform` (repo de cliente en labsryzen), commit `cb68b62` — v0.6.
- Build: `npx vite build --base=/guias/divine-light/` + `BrowserRouter` con `basename`
  derivado de `import.meta.env.BASE_URL`.
- Vista publicada: `/guias/divine-light/componentes` (la raíz redirige ahí).
- Spec de tokens: `design.md` v0.3.1 y `g-zuzel:03_Desarrollo/design.md`.

## Añadir una guía nueva

1. Compilar con `--base=/guias/<slug>/` y `basename` equivalente.
2. Copiar el `dist/` a `<slug>/`.
3. Añadir la tarjeta en `index.html` y actualizar el fallback de `404.html` si cambia el mapa de rutas.
