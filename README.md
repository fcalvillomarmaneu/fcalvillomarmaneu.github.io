# Web académica de Francisco Calvillo

Versión inicial preparada en **Quarto** para publicarse gratuitamente mediante **GitHub Pages**.

## Publicar por primera vez (sin programar)

1. En GitHub, abre **Settings → Pages** del repositorio `fcalvillomarmaneu.github.io`.
2. En **Build and deployment → Source**, elige **GitHub Actions**.
3. Descomprime el ZIP en tu ordenador y **entra dentro** de la carpeta descomprimida.
4. Si utilizas Mac, pulsa `⌘ + ⇧ + .` en Finder para mostrar los elementos ocultos, como `.github` y `.gitignore`.
5. En GitHub, entra en el repositorio y selecciona **Add file → Upload files**. Arrastra **todo el contenido** de la carpeta descomprimida (no arrastres el propio ZIP ni la carpeta contenedora). La estructura debe conservarse, en especial `.github/workflows/deploy.yml`.
6. Haz clic en **Commit changes** para guardar los archivos en la rama `main`.
7. Abre la pestaña **Actions**. La tarea «Publish academic website» debe terminar correctamente.
8. Visita `https://fcalvillomarmaneu.github.io/`. La primera publicación puede tardar unos minutos en aparecer.

## Editar después

- `index.qmd`: página principal
- `research.qmd`: líneas de investigación
- `publications.qmd`: artículos y preprints
- `teaching.qmd`: docencia
- `cv.qmd`: formación y CV
- `contact.qmd`: contacto
- `styles.scss`: colores y diseño
- `_quarto.yml`: menú, enlaces y configuración

Cuando tengas tu CV en PDF, podrás añadirlo al repositorio y enlazarlo desde `cv.qmd`. Si quieres poner una foto, tu correo profesional o tu enlace de ORCID, podemos incorporarlos después.

## Importante

- No se ha añadido una dirección de correo privado ni una foto sin tu permiso.
- El apartado de corrección de errores cuánticos está presentado como **interés de investigación en desarrollo**, no como una publicación o puesto de trabajo ya confirmado.
- El sitio usa GitHub Pages con **Source: GitHub Actions**; no hace falta crear una rama `gh-pages`.

## Referencias

- Documentación Quarto: https://quarto.org/docs/websites/
- Quarto y GitHub Pages: https://quarto.org/docs/publishing/github-pages.html
- Subida de archivos a GitHub: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
