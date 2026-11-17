# Aportes SAFYB · MDV Auditoría y Consultoría

Página web informativa con calculadora y control de aportes al SAFYB (Arts. 27, 28, 29, 30 y 32).

## Publicar en GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `mdv-aportes-safyb`).
2. Subí todo el contenido de esta carpeta a la rama `main`, incluida la carpeta oculta `.github`.
3. En el repositorio entrá a **Settings → Pages**.
4. En **Build and deployment → Source** elegí **GitHub Actions**.
5. Esperá a que termine la pestaña **Actions** (1 a 2 minutos).

La página queda en `https://TU-USUARIO.github.io/mdv-aportes-safyb/`.

## Cómo editar

Todo el sitio está en `index.html`. Cada cambio que subas a `main` se publica solo.

## Estructura

- `index.html`: la página (HTML, CSS y JavaScript en un solo archivo)
- `.github/workflows/pages.yml`: publicación automática
- `.nojekyll`: evita el procesamiento de Jekyll
