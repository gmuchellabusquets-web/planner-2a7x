# Agenda 2º Bach A: cómo publicarla e instalarla

Es una app web instalable (PWA). La subes gratis a GitHub Pages una vez y después la instalas en el PC y en el móvil.

## 1. Subirla a GitHub (solo la primera vez)

1. Entra en https://github.com con tu cuenta (si aún no tienes, créala: es la misma tarea de PTD2).
2. Arriba a la derecha, pulsa **+** → **New repository**.
   - Nombre: `planner-2a7x`
   - Márcalo como **Public**
   - Pulsa **Create repository**.
3. En la página del repositorio, pulsa **uploading an existing file**.
4. Arrastra estos 7 archivos (no la carpeta, los archivos sueltos):
   `index.html`, `data.json`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `LEEME.md`
5. Pulsa **Commit changes**.
6. Ve a **Settings** → **Pages** (menú de la izquierda).
   - En *Branch* elige **main** y la carpeta **/ (root)** → **Save**.
7. Espera 1–2 minutos y recarga. Arriba saldrá tu dirección, algo como:
   `https://TU-USUARIO.github.io/planner-2a7x/`

## 2. Instalarla

**PC (Chrome o Edge):** abre tu dirección. En la barra de direcciones aparece un icono de "Instalar" (una pantalla con una flecha). Pulsa → **Instalar**. Te queda en el escritorio y en el menú Inicio, y se abre en su propia ventana.

**Android (Chrome):** abre la dirección → menú ⋮ → **Instalar aplicación** (o "Añadir a pantalla de inicio").

**iPhone (Safari):** abre la dirección → botón **Compartir** → **Añadir a pantalla de inicio**.

Funciona también sin internet.

## 3. Cosas a saber

- **Los datos se guardan en cada dispositivo.** Para pasar tus tareas y notas del PC al móvil: en el PC pulsa **Exportar copia** (abajo del todo), envíate el archivo `.json` y en el móvil pulsa **Importar copia**.
- **Se actualiza sola.** Cada domingo Claude revisa Classroom y el calendario de tutoría y actualiza `data.json`; la app lo lee cada vez que la abres con internet. Tus marcas, notas y tareas propias no se tocan.
- **Para cambiar algo de la app**, pídeselo a Claude, sube el `index.html` nuevo al repositorio (Add file → Upload files → Commit) y la app se actualiza sola la siguiente vez que la abras con internet.
