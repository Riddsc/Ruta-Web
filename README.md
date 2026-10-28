# Ruta Web

Curso interactivo y gratuito de desarrollo web en español. Cada lección tiene teoría breve, un ejemplo y un reto que se escribe en un editor dentro de la página y se corrige automáticamente.

**13 niveles · 94 lecciones · unas 15 horas de práctica**

| Nivel | Contenido |
|---|---|
| 0 · Antes de empezar | Teclado de programador (símbolos por distribución), atajos, archivos y rutas, VS Code, cómo estudiar |
| 1 · HTML | Etiquetas, enlaces, imágenes, listas, semántica, formularios |
| 2 · CSS | Selectores, modelo de caja, Flexbox, Grid, responsive |
| 3 · JavaScript | Variables, funciones, arrays, objetos, DOM, eventos |
| 4 · Proyecto | Listas dinámicas, JSON, async/await, lista de tareas |
| 5 · HTML y CSS pro | Tablas, validación, accesibilidad, posicionamiento, animaciones, landing page |
| 6 · JavaScript moderno | Plantillas, bucles, desestructuración, métodos de arrays, errores, clases |
| 7 · Apps interactivas | Delegación, formularios, estado y render, búsqueda, localStorage, APIs |
| 8 · Herramientas | Terminal, Git, GitHub, GitHub Pages, DevTools, HTTP |
| 9 · CSS avanzado y UI | Temas, selectores, pseudo-elementos, sombras, componentes, modales |
| 10 · JavaScript avanzado | Closures, temporizadores, Set/Map, regex, `?.` y `??`, recursión, debounce |
| 11 · Lógica y algoritmos | FizzBuzz, palíndromos, anagramas, Big O, búsqueda binaria, pilas |
| 12 · Proyectos de portafolio | Divisor de cuentas, temporizador de rounds, trivia, juego, catálogo, buscador de películas |

Además: **Taller** (proyectos propios con `index.html`, `estilos.css` y `app.js` separados, plantillas, guardar en una carpeta del PC desde Chrome/Edge); **repaso inteligente** de las lecciones difíciles y **reto del día**; pantalla de inicio con progreso y racha; sección **Apuntes** con notas por lección, chuletas (HTML, CSS, JS, Git, atajos), guía y probador de teclado, glosario y plan de estudio posterior; insignias, certificado imprimible, tema claro/oscuro y copia de seguridad del progreso.

## Uso

La app es `index.html`. Publícala con GitHub Pages (Settings → Pages → rama `main`, carpeta `/ (root)`) y queda en `https://riddsc.github.io/Ruta-Web/`.

**Instalar como app (Windows, Chrome o Edge):** abre ese enlace y pulsa el botón **Instalar** de la barra superior (o el ícono de instalar en la barra de direcciones). Queda en el menú Inicio con su propia ventana y funciona sin internet. `manifest.webmanifest`, `sw.js` e `icons/` hacen posible la instalación.

Cada persona que abre el enlace tiene su propio progreso, guardado en su navegador (`localStorage`): lecciones, notas y proyectos del Taller. Desde **Logros** se descarga una copia y se restaura en otro dispositivo o navegador.

## Agregar una lección

Las lecciones están en el array `L` dentro de `index.html`. Cada una tiene `id`, `lvl` (nivel), `title`, `mins`, `theory`, `example`, `task`, `starter`, `solution`, `hints` y `tests`. Cada prueba recibe un contexto `c` con utilidades (`c.q`, `c.all`, `c.txt`, `c.cs`, `c.ev`, `c.rules`) y devuelve `true` si pasa. Las lecciones con `type: "quiz"` usan `questions` en lugar de editor.
