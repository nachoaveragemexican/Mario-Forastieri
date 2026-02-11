# Mario Forastieri — Entrenamiento de Ventas

Brochure digital para el servicio de entrenamiento de ventas presencial en Tijuana.

## Setup

1. Clona el repositorio
2. Agrega las fotos a la carpeta `images/` con los nombres indicados abajo
3. Cambia el número de WhatsApp en `index.html` (busca `XXXXXXXXXX` y reemplázalo con tu número completo, sin espacios ni guiones)
4. Haz deploy con GitHub Pages desde la rama `main`

## Fotos requeridas

Todas las fotos se colocan en la carpeta `images/`:

| Archivo | Ratio | Min. px | Descripción |
|---------|-------|---------|-------------|
| `hero-training.jpg` | 16:9 | 1920x1080 | Foto entrenando a un grupo. Toma amplia. |
| `team-workshop.jpg` | 3:2 | 1200x800 | Equipo trabajando: role-play o ejercicio grupal. |
| `headshot-mario.jpg` | 1:1 | 800x800 | Headshot profesional o candid de medio cuerpo. |

Las fotos se muestran automáticamente en blanco y negro via CSS. Solo coloca los archivos con los nombres exactos y aparecerán sin cambiar código.

## Deploy con GitHub Pages

1. Ve a Settings > Pages en tu repositorio de GitHub
2. En "Source", selecciona la rama `main` y la carpeta `/ (root)`
3. Guarda y espera unos minutos
4. Tu sitio estará en `https://tu-usuario.github.io/Mario-Forastieri/`

## Dominio custom (opcional)

Si tienes un dominio propio:
1. Edita el archivo `CNAME` con tu dominio (ejemplo: `ventas.marioforastieri.com`)
2. Configura los DNS de tu dominio apuntando a GitHub Pages
