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


## Sur One · Resultado de inspección vehicular (correos 06.1–06.6)

Imagenes de los 6 correos del flujo de pago posterior a la inspección. Los HTML (en el zip entregado) ya apuntan a estas URLs.

Base: `https://cdn.jsdelivr.net/gh/fideegz/surone-email-assets@main/inspeccion-vehicular/images/`

| Archivo | Medidas | Uso |
|---|---|---|
| header-surone-cifraseg.png | 1104x144 | Cabecera co-branding (06.6) |
| hero-inspeccion-rechazada.png | 1104x368 | Banner 06.5 |
| hero-resultado-inspeccion.png | 1104x368 | Banner 06.3 / 06.4 |
| hero-resultado-validacion.png | 1104x368 | Banner 06.1 / 06.2 |
| hero-vehiculo-nuevo.png | 1104x368 | Banner 06.6 |
| icon-advertencia.png | 112x112 | Ícono advertencia |
| icon-aprobado.png | 112x112 | Ícono estado aprobado |
| icon-corregir.png | 64x64 | Ícono datos por corregir |
| icon-facebook.png | 36x36 | Red social |
| icon-info.png | 64x64 | Ícono información |
| icon-instagram.png | 36x36 | Red social |
| icon-motivo.png | 64x64 | Ícono motivo |
| icon-rechazado.png | 112x112 | Ícono estado no aprobado |
| icon-youtube.png | 36x36 | Red social |
| logo-aseguradora-del-sur.png | 200x80 | Logo ADS en firma |
| logo-surone.png | 252x60 | Logo cabecera |
| logos-ads-sostenibilidad.png | 530x160 | Logos ADS + sostenibilidad (06.6) |


## Oficina Virtual APS · Aseguradora del Sur (notificaciones internas)

Imagenes de los correos de la Oficina Virtual APS (plantilla "D - Notificacion" de Figma). El HTML se entrega aparte y ya apunta a estas URLs.

Base: `https://cdn.jsdelivr.net/gh/fideegz/surone-email-assets@main/oficina-virtual-aps/images/`

| Archivo | Medidas | Uso |
|---|---|---|
| header-ejecutivo.jpg | 600x300 | Cabecera azul de correos internos (Mensaje=Ejecutivo) |
| logo-aseguradora-del-sur.png | 400x160 | Logo ADS en el pie (se muestra a 200x80) |
| icon-facebook.png | 48x48 | Red social (celeste, se muestra a 24x24) |
| icon-instagram.png | 48x48 | Red social (celeste, se muestra a 24x24) |
| icon-youtube.png | 48x48 | Red social (celeste, se muestra a 24x24) |
