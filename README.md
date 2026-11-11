# Maniobras Latam

Proyecto de la comunidad (no oficial) para seguir las Maniobras de World of Tanks en NA.

## Publicar en Cloudflare Pages
1. Sube estos archivos a un repositorio de GitHub (por ejemplo `maniobras-latam`).
2. En Cloudflare: Workers y Pages > Crear > Pages > Conectar con Git, y elige el repositorio.
3. Configuración de compilación: framework "None", comando de build vacío, directorio de salida `/`.
4. Guarda. La página queda en `nombre-del-proyecto.pages.dev`.

## Actualizar datos
Por ahora los datos de clanes están dentro de `index.html` (variable `R`, formato `posición,nombre,puntos`). Edita el archivo en GitHub y Cloudflare publica el cambio solo.

## Pendiente
- Logo de cada clan (archivo propio, subido al repositorio).
- Worker con la API de clanes de Wargaming (el Application ID va como secreto, nunca en el código).
- Base de datos D1 para el historial del corte.

## Créditos
Historial del corte: Clan IN-KA (claninka.com/maniobras). Reglas: anuncio oficial de Wargaming.
