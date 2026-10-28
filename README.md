# KODEX — Portal de marcas

Portal corporativo en español para kodex.com.do. Sitio estático, sin dependencias de compilación.

## Funciones
- Acceso a gaming.kodex.com.do y solutions.kodex.com.do desde los logos.
- Tema claro/oscuro con preferencia guardada y detección del sistema.
- Carrusel de tres banners con controles, pausa y soporte para movimiento reducido.
- Vitrina filtrable por marca, menú móvil y navegación por teclado.

## Desarrollo
Ejecutar `python3 -m http.server 8080 --directory dist` y abrir http://localhost:8080.
El contenido publicable está en `dist/`. Las fuentes son HTML, CSS y JavaScript estándar.

## Contenido
Las imágenes de categorías son ilustrativas (Unsplash). No se afirman precios, existencias ni especificaciones de modelos. Reemplazar con catálogo aprobado al disponer de él. Los logos provienen del propietario de KODEX. No modifican los repositorios ni las tiendas existentes.

## Publicación en GitHub Pages
El flujo `.github/workflows/pages.yml` publica `dist/` desde `main`. En Settings → Pages seleccionar GitHub Actions. Configurar `kodex.com.do` como dominio personalizado solo cuando DNS esté listo; activar HTTPS cuando GitHub emita el certificado. Ver DEPLOYMENT.md.
