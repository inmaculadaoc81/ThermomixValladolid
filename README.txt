THERMOMIXREPAIR VALLADOLID ONE PAGE

Zona: Valladolid (España)

Marca: ThermomixRepair® — "Su Servicio Técnico de Confianza"
Logo e isotipo: assets/logo-thermomixrepair.png y
assets/favicon-thermomixrepair.png (proporcionados por el cliente).
Ambos archivos traen fondo verde bosque oscuro opaco (#123b2c,
capturas, no PNG transparente). La cabecera, el footer y las
secciones oscuras se han igualado a ese mismo tono para que el logo
no muestre una caja visible.

Colores: paleta rebrandeada al verde bosque oscuro del logo (#123b2c)
+ un cian brillante (#12b4dd) y un verde-azulado medio (#0e7a6b),
en vez del verde lima de la plantilla original (ThermomixTech). El
color ámbar/dorado de la tarjeta TM7 "special" se mantiene tal cual,
ya que es un acento deliberado para diferenciarla del resto.

Dominio: https://reparacionrobotcocina.es/
(CONFIRMADO por el cliente. Corregido en canonical, og:url, JSON-LD,
robots.txt y sitemap.xml — antes apuntaban a
reparacionderobotcocina.com.es, el dominio de la versión de Madrid,
ThermomixTech.)

Teléfono caja y botones: +34 910 05 24 89 / +34 649 97 01 28 WhatsApp
(mantenidos tal cual, según indicación del cliente)

IMPORTANTE — dirección física:
No se proporcionó una dirección real para Valladolid. Se ha quitado
la dirección de Madrid (C. Joaquín María López, 26) y el bloque de
Metro/aparcamiento (específico de Madrid, sin sentido en Valladolid).
La caja de información ahora muestra "Zona de servicio: Valladolid
capital y alrededores" en su lugar. El enlace y el iframe de Google
Maps se han mantenido sin cambios (según indicación del cliente),
aunque siguen apuntando a la ubicación de Madrid — revisar si debe
sustituirse por una ficha de Google Business de Valladolid.

h1 actualizado (más corto, afirmativo, sin interrogación ni
condicionales, incluye la marca): "Tu Thermomix no funciona. La
revisamos con total confianza." Tamaño del H1 aumentado:
clamp(38-56px) → clamp(46-74px) en escritorio, 40px → 48px en móvil.

Modelos:
- TM21
- TM31
- TM5
- TM6
- TM7: SOLO cambio de cuchilla

El correo SMTP no aparece visible en la web; solo se utiliza en /api/contacto.
Variables Vercel compartidas: SMTP_HOST, SMTP_PORT=465, SMTP_SECURE=true, SMTP_USER, SMTP_PASS, CONTACT_EMAIL.
Google Analytics:
G-YSB012JKGC

HISTORIAL: el repositorio era multipágina (11 páginas /servicios/ de
averías y mantenimiento Thermomix) y se convirtió a one-page; esas
páginas fueron eliminadas en commits anteriores. Como ya no existen en
el sitemap actual, se ha añadido middleware.mjs para redirigir (301)
cualquier URL antigua a la home, evitando 404 en enlaces indexados o
backlinks antiguos. Excluye /api/* y cualquier ruta con extensión de
archivo. Se añadió "@vercel/functions": "^2.0.3" a package.json como
dependencia de esta función.

REVISIÓN (fixes aplicados en esta pasada):
- Ya estaba bien: banner de cookies (ya corregido en un commit
  anterior), schema.org LocalBusiness completo (con areaServed y
  sameAs), sección SEO, menú móvil, borde blanco del chat,
  api/contacto.js con SMTP + nodemailer. No se ha modificado ninguno
  de estos.
- Google Analytics: no existía. Añadido G-YSB012JKGC.
- .navcall: el texto largo ("Atención Telefónica 24 horas 365 días")
  deformaba la píldora del menú. Acortado a solo el número (mismo
  número, +34 910 05 24 89) y añadido white-space:nowrap como
  salvaguarda.

AVISOS RESUELTOS EN ESTA PASADA (mismo caso que DysonValladolid):
- Dominio confirmado por el cliente: https://reparacionrobotcocina.es/
  (corregido en canonical, og:url, JSON-LD, robots.txt, sitemap.xml).
- Teléfono y Google Maps: confirmado por el cliente que se mantienen
  igual que en ThermomixTech Madrid de forma intencional; no se han
  tocado.
