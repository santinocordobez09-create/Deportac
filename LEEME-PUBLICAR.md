# Pizarra Fit · cómo publicarla gratis en GitHub Pages

Archivos de esta carpeta (los 6 van juntos, en la misma carpeta):
index.html · manifest.json · sw.js · icon-192.png · icon-512.png · icon-maskable-512.png

## Paso a paso (10 minutos, sin instalar nada)
1. Entrá a https://github.com y creá una cuenta gratis (si no tenés).
2. Arriba a la derecha: "+" → "New repository". Nombre: `pizarra-fit`. Dejalo en **Public**. "Create repository".
3. En el repositorio nuevo: "uploading an existing file". Arrastrá los 6 archivos. Abajo: "Commit changes".
4. Andá a **Settings → Pages**. En "Build and deployment": Source = "Deploy from a branch". Branch = `main`, carpeta `/ (root)`. "Save".
5. Esperá 1 o 2 minutos y recargá esa pantalla: aparece tu dirección, del estilo `https://TU-USUARIO.github.io/pizarra-fit/`. Esa es tu app.

## Instalarla en el celular (queda como una app y funciona sin internet)
- Android (Chrome): abrí la dirección → menú ⋮ → "Instalar aplicación" (o el botón "Instalar" que aparece arriba en la app).
- iPhone (Safari): abrí la dirección → botón Compartir → "Agregar a pantalla de inicio".
La primera vez tiene que abrirse con internet; después funciona sin conexión.

## Para actualizar la app más adelante
Subí el nuevo `index.html` al mismo repositorio (Add file → Upload files → reemplaza). Si querés que los celulares
tomen el cambio enseguida, en `sw.js` cambiá `pizarra-fit-v3` por `pizarra-fit-v4`.

## Cosas para saber
- Todo lo que guardás (ejercicios, sesiones, audios) queda **en el navegador de ese dispositivo**. Si abrís la app en otro celular o
  computadora, empieza vacía. Para pasar datos: Biblioteca → "Copia de seguridad" → Descargar archivo (incluye audios) y en el otro equipo → Importar.
- No borres los datos del navegador sin haber hecho la copia de seguridad.
- Grabar audio con el micrófono funciona desde la dirección publicada (https). El navegador te va a pedir permiso una vez.
- Gratis: GitHub Pages no cobra por sitios públicos. Alternativas igual de simples: Netlify Drop (arrastrás la carpeta) o Cloudflare Pages.
