# Nutrición y gimnasio

App web con tres módulos: **Nutrición** (comidas, calorías, metas y peso), **Gimnasio** (mapa muscular, series y repeticiones) y **Resumen** (lo comido frente a lo quemado).

Diseñado por BG Solutions · bgiasolutions.cl

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa (todo en un solo archivo) |
| `manifest.webmanifest` | Permite instalarla como app en el teléfono |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon.png` | Íconos de la app |

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `nutricion-gym`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/nutricion-gym/`.

## Publicar con Render (como tus otras apps)

1. Sube los archivos a un repositorio de GitHub (pasos 1 y 2 de arriba).
2. En Render: **New → Static Site**, conecta el repositorio.
3. Deja *Build Command* vacío y en *Publish Directory* escribe `.`
4. Crea el sitio. Cada vez que subas cambios a GitHub, Render la actualiza solo.

## Instalarla en el iPhone

Abre el link en Safari → botón **Compartir** → **Agregar a pantalla de inicio**.

## Tus datos

- Esta versión guarda los datos **en el navegador de cada dispositivo** (no en la nube).
- La primera vez que se abre trae cargado tu historial (55 días de comidas, tu perfil y tu sesión de gimnasio).
- En la pantalla de inicio hay **Descargar respaldo** y **Restaurar respaldo**: úsalos de vez en cuando y para pasar los datos del teléfono al computador o a otro equipo.
- Si borras los datos de Safari o desinstalas el acceso directo, se pierde lo que no esté respaldado.
- Las fotos de los ejercicios solo están disponibles en la versión de claude.ai.

## Accesos directos

- `.../#nutricion` abre directo Nutrición
- `.../#gimnasio` abre directo Gimnasio
- `.../#resumen` abre directo Resumen
