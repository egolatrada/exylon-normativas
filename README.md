# Normativa EXYLON (web estática)

Sitio estático con la normativa de **comercios** y **talleres**. Entrada: `index.html`.

## Google Sites

En **Google Sites** no puedes subir una carpeta con varios `.html` enlazados como un hosting normal. Tendrías que copiar el texto a páginas del sitio o incrustar otra URL en un marco; no es lo adecuado para este proyecto.

## Publicar con GitHub Pages

1. Crea en GitHub un repositorio **vacío** (sin README) si aún no existe, por ejemplo `exylon-normativas`.
2. En esta carpeta (`Whatsapp Trabajo`), el remoto debe apuntar a tu repo. Si ya existe `origin` con otra URL:

   ```bash
   git remote set-url origin https://github.com/egolatrada/exylon-normativas.git
   git branch -M main
   git push -u origin main
   ```

   Si **no** tenías `origin`, entonces:

   ```bash
   git remote add origin https://github.com/egolatrada/exylon-normativas.git
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Build and deployment → Source**: elige **Deploy from a branch**, rama **main**, carpeta **/ (root)**. Guarda.
4. En unos minutos tendrás una URL del tipo:

   `https://egolatrada.github.io/exylon-normativas/`

   La página principal será `index.html`.

### Si GitHub te pide autenticación

Usa un **Personal Access Token** (classic) con permiso `repo` en lugar de la contraseña, o inicia sesión con **GitHub Desktop**.

## Archivos

| Archivo | Uso |
|---------|-----|
| `index.html` | Portada con enlaces |
| `normativa-negocios.html` | Normativa de comercios |
| `normativa-talleres.html` | Normativa de talleres |
