# Yū · 優

App personal para conocer la cultura japonesa a través de sus kanji.
**Creado por melitalove · Sabiduría antigua para tu presente**

Versión actual: 第六版 · versión 6

## Secciones
- **Hoy**: kanji del día, sus partes, historia real, lectura cultural y pregunta para el diario.
- **Explorar**: Aprender, Colección, Estaciones, Cielo, Construir (3 niveles) y Mi kanji (buscador de 2.136 kanji).
- **Shodō**: escribir kanji con el dedo, con corrección del orden de trazos y un tema nuevo cada semana.
- **Diario** y **Perfil**.

## Archivos
| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La app completa |
| `manifest.webmanifest` | Nombre, colores e íconos al instalarla |
| `sw.js` | Permite abrirla sin internet |
| `kanji-es.json` | Diccionario de kanji con significados en español |
| `trazos.json` | Orden de trazos de cada kanji |
| `*.png`, `*.svg` | Íconos |

Todos los archivos van sueltos en la raíz del repositorio, sin carpetas.

## Publicar en GitHub Pages
1. Crea un repositorio público llamado `yu`.
2. Sube todos los archivos con **Add file → Upload files** y toca **Commit changes**.
3. Ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En unos minutos la app queda en `https://melilove.github.io/yu/`.

## Instalar en Android
Abre la dirección en Chrome, toca ⋮ y elige **Instalar app**.

## Al actualizar
Cambia en `sw.js` la línea `const VERSION = 'yu-v6';` y en `index.html` la línea `var APP_VERSION = 6;` por el número siguiente.

## Créditos
- Trazos: [KanjiVG](https://kanjivg.tagaini.net), de Ulrich Apel, licencia CC BY-SA 3.0.
- Significados y lecturas: [KANJIDIC2](https://www.edrdg.org/wiki/index.php/KANJIDIC_Project), de EDRDG, licencia CC BY-SA 4.0.
