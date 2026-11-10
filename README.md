# Principios de Economía II · FCE · UNT

Página de la materia: diapositivas, guías de estudio y material del cursado.

## Estructura

- `index.html`: la página (todo en un solo archivo, con los colores de las clases).
- `guias/`: guías de estudio en PDF (`guia-tema-5.pdf`, `guia-tema-6.pdf`, …).
- `.nojekyll`: indica a GitHub Pages que publique los archivos tal cual.

## Cómo publicarla con GitHub Pages

1. Crear un repositorio nuevo en github.com (por ejemplo `macro-unt`), público.
2. En el repositorio: **Add file → Upload files** y arrastrar `index.html`, `README.md`, `.nojekyll` y la carpeta `guias`. Confirmar con **Commit changes**.
3. Ir a **Settings → Pages**. En *Source* elegir **Deploy from a branch**, rama **main**, carpeta **/ (root)** y **Save**.
4. En uno o dos minutos la página queda en `https://<tu-usuario>.github.io/macro-unt/`.

## Cómo sumar un tema nuevo

1. Subir la guía en PDF a `guias/` con el nombre `guia-tema-N.pdf`.
2. En `index.html`, copiar el bloque `<section id="tema-6">…</section>`, cambiar número, título, frase y los links de las clases.
3. En la tarjeta del tema (sección "Temas del cursado"), sacar la clase `soon` y cambiar el texto "Próximamente" por el link `Ver guía y clases →`.
