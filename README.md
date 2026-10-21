# Yū · 優

App personal para conocer la cultura japonesa a través de sus kanji.
**Creado por melitalove · Sabiduría antigua para tu presente**

## Secciones
- **Hoy**: kanji del día, sus partes, historia real, lectura cultural y pregunta para el diario.
- **Explorar**: Colección, Estaciones (24 estaciones japonesas), Cielo (la semana y los planetas), Construir (unir piezas) y Mi kanji (buscar el kanji de una palabra).
- **Shodō**: escribir kanji con el dedo y ver el orden de trazos.
- **Diario** y **Perfil**.

## Archivos
| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La app completa |
| `manifest.webmanifest` | Nombre, colores e íconos al instalarla |
| `sw.js` | Permite abrirla sin internet |
| `icons/` | Íconos en todos los tamaños |

## Publicar en GitHub Pages
1. Crea un repositorio nuevo (por ejemplo `yu`).
2. Sube **todo el contenido** de esta carpeta, incluida la carpeta `icons`.
3. Ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En unos minutos la app queda en `https://TU-USUARIO.github.io/yu/`.

## Instalar en Android
1. Abre la dirección en **Chrome**.
2. Toca el menú ⋮ y elige **Instalar app** (no "Añadir a pantalla de inicio").
3. Si ya tenías un acceso directo antiguo, bórralo antes.

## Al hacer cambios
Si modificas `index.html`, cambia en `sw.js` la línea `const VERSION = 'yu-v1';` por `yu-v2`, `yu-v3`, etc., para que el celular cargue la versión nueva.

## Créditos
Trazos de los kanji: [KanjiVG](https://kanjivg.tagaini.net), de Ulrich Apel, licencia CC BY-SA 3.0.
