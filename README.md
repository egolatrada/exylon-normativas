# Normativa EXYLON (web estática)

Sitio estático con la normativa de **comercios** y **talleres**. Entrada: `index.html`.

## Google Sites

En **Google Sites** no puedes subir una carpeta con varios `.html` enlazados como un hosting normal. Tendrías que copiar el texto a páginas del sitio o incrustar otra URL en un marco; no es lo adecuado para este proyecto.

## Publicar con GitHub Pages

1. Crea en GitHub un repositorio **vacío** (sin README), por ejemplo `normativa-exylon`.
2. En esta carpeta (`Whatsapp Trabajo`), ejecuta (cambia `TU_USUARIO` y el nombre del repo):

   ```bash
   git remote add origin https://github.com/TU_USUARIO/normativa-exylon.git
   git branch -M main
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Build and deployment → Source**: elige **Deploy from a branch**, rama **main**, carpeta **/ (root)**. Guarda.
4. En unos minutos tendrás una URL del tipo:

   `https://TU_USUARIO.github.io/normativa-exylon/`

   La página principal será `index.html`.

### Si GitHub te pide autenticación

Usa un **Personal Access Token** (classic) con permiso `repo` en lugar de la contraseña, o inicia sesión con **GitHub Desktop**.

## Archivos

| Archivo | Uso |
|---------|-----|
| `index.html` | Portada con enlaces |
| `normativa-negocios.html` | Normativa de comercios |
| `normativa-talleres.html` | Normativa de talleres |
