# Cómo publicar las páginas legales de HeartCheck en GitHub Pages (SIN subir el código privado)

> **Seguridad:** Nunca subas la carpeta completa del proyecto ni el archivo `.env` a un repositorio público. Sube **únicamente** los 5 archivos HTML/CSS de esta carpeta (`index.html`, `privacy.html`, `terms.html`, `data-deletion.html`, `styles.css`).

## Pasos para principiantes

1. Antes de subirlos, abre `privacy.html`, `terms.html` y `data-deletion.html` y reemplaza `[COMPLETAR: ...]` por tu nombre/equipo y un correo real de contacto.
2. Entra a `https://github.com/` e inicia sesión.
3. Pulsa **+ → New repository**.
   - **Repository name:** `heartcheck-legal`
   - Visibilidad: **Public** (obligatorio para GitHub Pages gratuito).
   - Pulsa **Create repository**.
4. Dentro del nuevo repositorio vacío, haz clic en **uploading an existing file**.
5. Arrastra únicamente estos 5 archivos de `public-legal-pages/`:
   - `index.html`
   - `privacy.html`
   - `terms.html`
   - `data-deletion.html`
   - `styles.css`
6. Pulsa **Commit changes**.
7. Ve a la pestaña **Settings** del repositorio → menú izquierdo **Pages**.
8. En **Build and deployment → Source**, elige **Deploy from a branch** → rama **main** → carpeta **/ (root)** → **Save**.
9. Espera 1–2 minutos y recarga la página; GitHub mostrará tu URL pública, por ejemplo:
   `https://TU_USUARIO.github.io/heartcheck-legal/`
10. Tus 3 URLs oficiales para pegar en **Meta Developers** serán:
    - **Política de Privacidad:** `https://TU_USUARIO.github.io/heartcheck-legal/privacy.html`
    - **Términos de Servicio:** `https://TU_USUARIO.github.io/heartcheck-legal/terms.html`
    - **Eliminación de Datos:** `https://TU_USUARIO.github.io/heartcheck-legal/data-deletion.html`
