# Test Master

Aplicación web para organizar documentos de estudio y crear/practicar tests.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube **todo el contenido** de esta carpeta a la raíz del repositorio.
3. En GitHub, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera a que GitHub Pages publique la aplicación.

La dirección tendrá esta forma:

`https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

## Archivos

- `index.html`: aplicación web.
- `.nojekyll`: evita el procesamiento Jekyll de GitHub Pages.

## Requisitos y límites actuales

- La aplicación guarda datos localmente en el navegador/dispositivo.
- La exportación de datos no incluye los PDF originales; conserva los PDF por separado.
- No hay sincronización automática entre dispositivos.
- Algunas funciones de lectura PDF/OCR cargan bibliotecas externas y necesitan conexión a Internet.
- Para usar SHA-256, abre la aplicación mediante HTTPS (GitHub Pages ya utiliza HTTPS) o `localhost`.
- GitHub Pages aloja la web estática; no proporciona por sí mismo una base de datos ni IA generativa.

## Actualizaciones

Para publicar una nueva versión, reemplaza `index.html` en el repositorio y confirma los cambios.
