# Juegos de Primaria

Pequeños juegos educativos en HTML para 5.º de Primaria. No necesitan instalación ni servidor: cada juego es un único archivo `index.html`.

| Juego | Tema | Carpeta |
|---|---|---|
| 🌍 Explorador del Mundo | Continentes y océanos | `mapas/` |
| 🔬 Laboratorio de Células | Célula eucariota animal y vegetal | `celulas/` |

## Probarlos en local

Abre `index.html` en el navegador. También puedes abrir directamente `mapas/index.html` o `celulas/index.html`.

## Publicar con GitHub Pages

1. Sube el repositorio a GitHub (rama `main`).
2. En el repositorio: **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Espera un minuto. La web quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Notas

- El progreso de cada juego se guarda en el navegador (`localStorage`). No se envía a ningún servidor.
- Las tipografías vienen de Google Fonts. Sin conexión se usa una fuente del sistema.
- El mapa se generó a partir de datos de Natural Earth (dominio público) mediante `world-atlas`. Los límites de los océanos son aproximados.
