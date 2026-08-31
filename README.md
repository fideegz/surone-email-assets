# Sur One - Cliente (email)

Assets e HTML de la plantilla de email **Sur One - Cliente**, para usar en Infobip.

## Archivos

| Archivo | Uso |
|---|---|
| `index-infobip.html` | **Pegar este en Infobip.** Imagenes referenciadas por URL absoluta (CDN jsDelivr). ~50 KB. |
| `index-base64.html` | Version autocontenida (imagenes en base64). Solo para previsualizar en navegador o archivar. ~1.4 MB. NO usar en email. |
| `index-original.html` | Original con rutas relativas `images/`. |
| `images/` | Imagenes originales (PNG). |

## URLs de las imagenes (CDN)

Base: `https://cdn.jsdelivr.net/gh/fideegz/surone-email-assets@main/images/`

| Archivo | Medidas | Uso en la plantilla |
|---|---|---|
| image-1.png | 268x64 | Logo cabecera |
| image-2.png | 1200x480 | Fondo hero (`background=`) |
| image-3.png | 600x240 | Fondo hero para Outlook (VML) |
| image-4.png | 96x96 | Icono |
| image-5.png | 744x268 | Imagen de contenido |
| image-6.png | 480x4 | Separador |
| image-7.png | 244x160 | Badge / store |
| image-8.png | 1x144 | Espaciador |
| image-9.png | 206x160 | Badge / store |
| image-10.png | 160x160 | Logo pie |
| image-11..14.png | 48x48 | Iconos redes sociales |

Para fijar una version inmutable, reemplazar `@main` por el SHA del commit.
