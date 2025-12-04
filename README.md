# MECASOFT Landing Page

Landing page estática para MECASOFT - Production Management SaaS.

## Estructura de Archivos

```
landing/
├── index.html              # Página principal
├── privacy-policy.html     # Política de privacidad
├── terms-of-service.html   # Términos de servicio
├── robots.txt              # Configuración para crawlers
├── sitemap.xml             # Mapa del sitio
├── site.webmanifest        # Manifest para PWA
├── favicon.ico             # Favicon (generar)
├── favicon-16x16.png       # Favicon 16x16 (generar)
├── favicon-32x32.png       # Favicon 32x32 (generar)
└── apple-touch-icon.png   # Icono para iOS (generar)
```

## Iconos y Favicons

El logo utiliza el icono de industria (`fa-industry`). Para generar los favicons:

1. **Crear un diseño base**: Icono de engranaje/industria en naranja (#f97316) sobre fondo oscuro
2. **Tamaños necesarios**:
   - `favicon.ico`: 16x16, 32x32, 48x48 (multi-resolución)
   - `favicon-16x16.png`: 16x16px
   - `favicon-32x32.png`: 32x32px
   - `apple-touch-icon.png`: 180x180px

### Herramientas recomendadas para generar favicons:
- [Favicon.io](https://favicon.io/)
- [RealFaviconGenerator](https://realfavicongenerator.net/)
- [Favicon Generator](https://www.favicon-generator.org/)

## Despliegue

Esta landing page es estática y puede desplegarse en:
- GitHub Pages
- Netlify
- Vercel
- Cualquier servidor web estático

## Notas

- Todos los enlaces internos usan rutas relativas (`./`)
- Los enlaces externos apuntan a `https://mecasoft.pro`
- El formulario de Brevo se abre en nueva pestaña
- Las páginas legales mencionan Brevo como responsable del procesamiento de emails

