# Órbita Integral

**Estrategia que conecta. Gestión que transforma.**

Sitio corporativo estático listo para GitHub Pages. Incluye las tres líneas
de servicios (Estrategia, Creativa y Emprende), historia, ventajas, misión,
visión, valores, metodología, portafolio y contacto.

## Publicar desde la web de GitHub

1. Descomprime `orbita-integral-github.zip` en tu computadora.
2. Crea en GitHub un repositorio llamado, por ejemplo, `orbita-integral`.
   Puedes usar un repositorio público si deseas publicar con GitHub Free.
3. Entra al repositorio y selecciona **Add file → Upload files**.
4. Sube **el contenido** de la carpeta descomprimida: `index.html`,
   `styles.css`, `app.js`, la carpeta `assets` y los demás archivos.
   `index.html` debe quedar directamente en la raíz del repositorio.
   No subas el ZIP sin descomprimir ni una carpeta contenedora adicional.
5. Confirma la subida con **Commit changes** en la rama `main`.
6. Abre **Settings → Pages**. En **Build and deployment → Source**,
   selecciona **Deploy from a branch**.
7. Selecciona la rama **main** y la carpeta **/ (root)**. Pulsa **Save**.
8. Espera a que termine la publicación. En esa misma pantalla aparecerá
   el enlace de tu web, normalmente `https://TU-USUARIO.github.io/orbita-integral/`.

El archivo `.nojekyll` es opcional para estos archivos y evita que se procesen
con Jekyll. Si tu explorador oculta archivos que empiezan por punto, puedes
crearlo en GitHub con **Add file → Create new file**.

Referencia oficial:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Ver la web en tu computadora

Abre `index.html` en un navegador. Para probarla mediante un servidor local,
si tienes Python instalado, ejecuta en esta carpeta:

```sh
python3 -m http.server 8000
```

Después abre `http://localhost:8000`.

## Archivos y edición

- `index.html`: contenido principal, secciones, formulario y enlaces.
- `styles.css`: diseño, colores, tipografías y adaptación a móviles.
- `app.js`: servicios desplegables, selector de necesidades, metodología
  y preparación de consultas.
- `assets/`: logo, fotografía y favicon.

No requiere Node.js, WordPress, base de datos ni compilación. Los recursos usan
rutas relativas para funcionar también bajo la carpeta de un repositorio.
Las fuentes se cargan desde Google Fonts, con alternativas del sistema.

## Contacto

WhatsApp: **+51 991 229 239**.
Correo: **orbita.integral.consultoria@gmail.com**.

El formulario prepara un mensaje que el visitante revisa y confirma en
WhatsApp o su aplicación de correo. No almacena consultas ni envía correos
desde un servidor. Si cambias el contacto, actualiza tanto `index.html`
como `app.js`. El portafolio mantiene espacios reservados para las marcas.

## Verificación

Se comprobaron la sintaxis JavaScript, los recursos locales, los enlaces
internos y la integridad del ZIP. La publicación en tu cuenta de GitHub
queda a tu cargo; este paquete no crea un repositorio ni publica por sí solo.
