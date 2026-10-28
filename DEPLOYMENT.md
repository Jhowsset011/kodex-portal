# Dominio y despliegue

Dominio principal: kodex.com.do. DNS administrado en NIC.DO (confirmado por el propietario).

El portal solo enlaza a los dos subdominios. Sus aplicaciones, DNS y certificados requieren despliegues independientes; no se han modificado aquí.

## GitHub Pages
Tras activar Pages, su configuración muestra el dominio técnico exacto. Para el dominio raíz, usar los registros vigentes de la documentación oficial de GitHub Pages. No reemplazar NS ni MX del dominio. Eliminar conflictos solo después de inspeccionar los registros actuales. Añadir el dominio en Settings → Pages y esperar la validación y el certificado HTTPS.

Referencia: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Edición
Banners y categorías: dist/app.js. Secciones y enlaces: dist/index.html. Diseño: dist/styles.css. Logos: dist/assets/.
