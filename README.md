# FitCoach

Aplicación de entrenamiento para el 10K: plan de la semana, registro de sesiones, fuerza con peso corporal y progreso.
Funciona sin conexión. Los datos se guardan **solo en el teléfono** (no hay servidor ni cuentas).

## Publicar en GitHub Pages
1. Sube estos archivos a la raíz del repositorio: `index.html`, `manifest.json`, `sw.js`, `logo.webp`, `README.md` y la carpeta `icons/`.
   (`logo.svg` y `mascot.svg` de versiones anteriores ya no se usan; puedes borrarlos.)
2. En el repositorio: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`**.
3. Espera 1–2 minutos y abre la dirección que muestra GitHub Pages.

## Instalar en el iPhone
1. Abre la dirección en **Safari**.
2. Toca **Compartir** → **Agregar a pantalla de inicio** → **Agregar**.
3. Abre FitCoach siempre desde ese ícono.

## Respaldo
En **Perfil → Respaldo**, guarda una copia cada semana en Archivos. Si el iPhone borra los datos de Safari, **Recuperar respaldo** los devuelve.
La imagen propia del logo no va en el respaldo.

## Actualizar
- Al subir una versión nueva, cambia `APP_BUILD` en `index.html` y `CACHE_VERSION` en `sw.js`.
- En el teléfono: toca **↻** arriba. Busca la versión nueva, borra solo la caché de la app y recarga. **No borra los datos.**
- Después de actualizar, Hoy muestra una vez **"Versión nueva: qué cambió"**.

## Cambiar el ícono de la pantalla de inicio
El iPhone guarda el ícono al instalar. Para ver un ícono nuevo:
1. **Perfil → Guardar respaldo** (borrar la app instalada borra sus datos).
2. Borra FitCoach de la pantalla de inicio y vuelve a agregarlo desde Safari.
3. **Perfil → Recuperar respaldo**.

## Accesibilidad
- Tema automático, claro, oscuro y **Sol** (alto contraste para leer bajo el sol).
- Texto Normal o Grande y **letra en negrita** (activa por defecto).
- Respeta "Reducir movimiento", "Aumentar contraste" y los colores forzados del sistema.
- Funciona con VoiceOver y con teclado. Los botones miden 44 px o más.
