# Reglas de esta demo

Lee `BRIEF.md` antes de nada. Usa la skill `estudio-web` para la dirección de arte y la revisión final.

## Stack
- Astro + Tailwind (`@tailwindcss/vite`), igual que el resto de demos de charcoles-hub.
- `astro.config.mjs` con `site: 'https://charcoles-hub.github.io'` y `base: '/demo-asesoria-proyecto-fm'`. Todas las rutas
  de assets tienen que funcionar con ese base.
- El despliegue lo hace `.github/workflows/deploy.yml` al llegar a `main`. No lo toques.

## Obligatorio
- `<meta name="robots" content="noindex, nofollow">` en el layout: no es la web oficial del negocio.
- Franja discreta arriba: "Propuesta de diseño para Asesoría Proyecto FM · preparada por Sergio García"
  con enlace a https://sergiogarciaweb.com.
- **Nada inventado.** Ni reseñas, ni testimonios, ni precios, ni años de experiencia, ni premios que no
  salgan de su web o de su ficha de Google. Si falta un dato, se omite. Nota de Google: 4,9 (142 reseñas).
- Sin comentarios en el código.

## Al terminar
Resume qué has cambiado respecto a su web actual y qué datos no has encontrado.
