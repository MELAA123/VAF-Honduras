# Sitio web de VAF — GitHub Pages

Plantilla inicial de una página informativa para Viviendo en Amor y Fe (VAF), con estilo natural, cálido y colores verde oliva y crema.

## Archivos
- `index.html`: contenido y secciones.
- `styles.css`: colores, diseño adaptable y estilos.
- `script.js`: menú móvil, año automático y ampliación de fotografías.
- `images/`: fotografías que se pueden añadir.

## Publicar gratis con GitHub Pages
1. Inicia sesión en https://github.com/
2. Pulsa **+** y luego **New repository**.
3. Escribe un nombre, por ejemplo `vaf-honduras`.
4. Selecciona **Public**. Marca **Add a README file** si lo deseas y crea el repositorio.
5. En el repositorio, pulsa **Add file** → **Upload files**.
6. Descomprime este ZIP en tu computadora. Arrastra `index.html`, `styles.css`, `script.js`, `.nojekyll` y la carpeta `images` desde la carpeta descomprimida al área de carga de GitHub. No subas el archivo ZIP dentro del repositorio como único archivo.
7. En **Commit changes**, confirma la carga.
8. Abre **Settings** → **Pages**.
9. En **Build and deployment**, elige **Deploy from a branch**. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
10. Espera unos minutos y vuelve a **Settings → Pages**. GitHub mostrará la dirección publicada. Si el repositorio se llama `vaf-honduras`, normalmente será `https://TU-USUARIO.github.io/vaf-honduras/`.

## Añadir las fotografías de la iglesia
1. Prepara copias de fotografías autorizadas, preferiblemente en JPG o WebP.
2. En la carpeta `images`, reemplaza o agrega estos archivos con los nombres exactos:
   - `portada.jpg`
   - `galeria-1.jpg`
   - `galeria-2.jpg`
   - `galeria-3.jpg`
   - `galeria-4.jpg`
3. En GitHub, entra en `images` y usa **Add file → Upload files** para subirlas.
4. Confirma con **Commit changes**. La página se actualizará automáticamente al terminar la publicación.

Si tus fotos tienen nombres distintos, puedes renombrarlas como arriba o editar la ruta en `index.html`.

## Antes de publicar para toda la iglesia
- Confirma la historia, misión, visión y creencias oficiales.
- Sustituye los textos provisionales de horarios y ubicación.
- Confirma el punto exacto del mapa; no se ha insertado una ubicación inventada.
- Publica solamente fotos con autorización, especialmente las de menores de edad.
- Recuerda que un repositorio público permite que otras personas vean el código y las fotos que subas.

## Editar el contenido
En GitHub, abre `index.html`, pulsa el lápiz para editar y luego **Commit changes**. Para cambiar colores o estilos, abre `styles.css`. Cada cambio se publica después de que GitHub Pages termine de actualizar el sitio.

## Nota
Esta es una página estática: no tiene un panel privado para que otros miembros publiquen anuncios. Para la primera versión, las actualizaciones se hacen editando los archivos del repositorio.
