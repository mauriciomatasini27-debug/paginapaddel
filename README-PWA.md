# Configuración PWA - Padel Listo

## Archivos Creados

1. **manifest.json** - Configuración de la PWA
2. **sw.js** - Service Worker para funcionalidad offline
3. **index.html** - Actualizado con meta tags y registro del service worker

## Iconos Necesarios

Para que la PWA funcione completamente, necesitas crear dos iconos:

- **icon-192.png** (192x192 píxeles)
- **icon-512.png** (512x512 píxeles)

### Opciones para crear los iconos:

1. **Herramientas online:**
   - [PWA Asset Generator](https://github.com/onderceylan/pwa-asset-generator)
   - [RealFaviconGenerator](https://realfavicongenerator.net/)
   - [PWA Builder](https://www.pwabuilder.com/imageGenerator)

2. **Desde una imagen:**
   - Usa una imagen del logo de Padel Listo
   - Redimensiona a 192x192 y 512x512 píxeles
   - Guarda como PNG con fondo transparente o color sólido

3. **Generar con código:**
   - Puedes usar herramientas como ImageMagick o librerías de Node.js

## Características PWA Implementadas

✅ Manifest.json configurado
✅ Service Worker para cache offline
✅ Meta tags para iOS y Android
✅ Botón de instalación personalizado
✅ Funcionalidad offline básica
✅ Actualización automática del service worker

## Pruebas

1. **Chrome DevTools:**
   - Abre DevTools (F12)
   - Ve a "Application" > "Service Workers"
   - Verifica que el service worker esté registrado

2. **Lighthouse:**
   - Abre DevTools > Lighthouse
   - Ejecuta auditoría PWA
   - Debería mostrar que es instalable

3. **Instalación:**
   - En Chrome/Edge: Busca el ícono de instalación en la barra de direcciones
   - En móvil: El navegador mostrará un banner de instalación

## Notas

- El service worker cachea recursos básicos para funcionamiento offline
- Los iconos son necesarios para que la PWA sea completamente funcional
- Asegúrate de servir el sitio con HTTPS (requerido para PWA en producción)

