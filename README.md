# MateriaLab

Aplicación web estática para estudiar Materiales I desde celular, tablet o computadora.

## Abrirla

La forma más simple es abrir `index.html` en un navegador moderno. Para habilitar el modo instalable y el funcionamiento sin conexión, inicia un servidor local en esta carpeta, por ejemplo:

```powershell
& "C:\Users\USUARIO\.cache\codex-runtimes\codex-primary-runtime\dependencies\python\python.exe" -m http.server 8080
```

Luego abre `http://localhost:8080/app/`.

## Arquitectura

- `index.html`: estructura semántica de las nueve vistas.
- `styles.css`: sistema visual responsivo, modo claro/oscuro e impresión.
- `main.v4.js`: contenido, navegación, actividades, evaluación y persistencia en `localStorage`.
- `sources.json`: relación entre módulos/preguntas y páginas de los PDF.
- `sw.js`: caché básico para uso sin conexión cuando se sirve por HTTP.

No requiere backend. El progreso se guarda únicamente en el navegador del dispositivo.
