# Dominio y despliegue

Dominio principal: kodex.com.do. DNS administrado en NIC.DO (confirmado por el propietario).

El portal solo enlaza a los dos subdominios. Sus aplicaciones, DNS y certificados requieren despliegues independientes; no se han modificado aquí.

## GitHub Pages
Tras activar Pages, su configuración muestra el dominio técnico exacto. Para el dominio raíz, usar los registros vigentes de la documentación oficial de GitHub Pages. No reemplazar NS ni MX del dominio. Eliminar conflictos solo después de inspeccionar los registros actuales. Añadir el dominio en Settings → Pages y esperar la validación y el certificado HTTPS.

Referencia: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Edición
Banners y categorías: dist/app.js. Secciones y enlaces: dist/index.html. Diseño: dist/styles.css. Logos: dist/assets/.

## Registros para NIC.DO

| Tipo | Nombre | Valor |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | jhowsset011.github.io |

TTL A: 7200 (mínimo admitido por NIC.DO); CNAME: 28800 (valor existente). Conservar los registros de correo y los de gaming/solutions. El dominio personalizado debe añadirse en GitHub Pages antes de aplicar los registros.

## Estado aplicado — 27 de octubre de 2026

- Repositorio nuevo: https://github.com/Jhowsset011/kodex-portal
- GitHub Pages activo con despliegue automático desde main.
- Dominio personalizado kodex.com.do guardado en GitHub Pages.
- Los cuatro registros A del dominio raíz y el alias www fueron añadidos en NIC.DO y confirmados como Active.
- Registros previos gaming y finanzas conservados.
- Solutions no tiene sitio desplegado ni registro DNS; el portal incorpora el enlace solicitado.
- La propagación y emisión HTTPS dependen del proveedor.
