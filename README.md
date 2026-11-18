# PubliFuturo · Portafolio de servicios

Sitio estático para Vercel: no necesita build, base de datos ni variables de entorno.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | El sitio, con estilos, textos, precios y páginas |
| `servicios.js` | El portafolio con todas sus fotos adentro. Se descarga una vez y queda en caché |
| `portafolio.html` | Portafolio en pantalla completa, en `/portafolio` |
| `propuesta.html` | Propuesta de desarrollo web, en `/propuesta` |
| `demo.html` | Demo en vivo del sistema administrativo, en `/demo` |
| `og.jpg` | Imagen que se ve al compartir el enlace |
| `vercel.json` | Rutas y caché |

## Páginas

- `#/`: portafolio completo y, debajo, las 9 unidades de negocio.
- `#/servicios`: todas las unidades.
- `#/servicios/desarrollo-web`, `verificacion-pagos`, `editor-video`, `redes-sociales`, `campanas`, `inteligencia-artificial`, `campanas-masivas` y `cursos`: una página por unidad.
- `#/sistema`: sistema administrativo y contable, con su demo.
- `#/contacto`: datos de contacto.

## Publicar

1. Crea un repositorio nuevo en GitHub, por ejemplo `publifuturo-servicios`.
2. Sube **todos los archivos de esta carpeta a la raíz** del repositorio. No los metas dentro de otra carpeta.
3. En Vercel, entra a **Add New → Project** e importa el repositorio.
   - Framework Preset: **Other**.
   - No cambies nada más.
   - Presiona **Deploy**.
4. Para usar tu dominio, entra a **Settings → Domains** en Vercel.

## Editar

- **Textos, precios e imágenes de cada unidad:** en `index.html`, busca `const UNITS`.
- **WhatsApp, correo, dirección y horario:** en `index.html`, busca `const CONTACTO`.
- **El portafolio** (`servicios.js` y `portafolio.html`) se genera aparte. Pídelo actualizado cuando cambie.
