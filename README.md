# Process Mining · Compras y recepción

Aplicación web estática para explorar procesos de compras y recepción mediante Process Mining.

## Estado actual

- Prototipo funcional basado en datos sintéticos.
- Mapa de proceso navegable con zoom y desplazamiento.
- Filtros por proveedor, categoría, resultado y periodo.
- Selección de actividades y transiciones para explorar órdenes.
- Variantes de proceso, tiempos entre eventos y cuellos de botella.
- Sin conexión a Odoo ni a fuentes externas todavía.

## Ejecutar localmente

Cuando `index.html` esté en el directorio raíz, ábrelo directamente en un navegador moderno. No requiere instalación ni servidor para la demo estática.

## Datos y privacidad

Los datos actuales son ficticios y se generan en el navegador. No se deben incorporar credenciales, secretos ni datos personales o productivos al repositorio.

## Flujo de cambios

1. Crear una rama por mejora.
2. Desarrollar y validar el cambio.
3. Abrir un Pull Request hacia `main`.
4. Revisar diferencias y probar la aplicación antes de integrar.

## Publicación

El objetivo es publicar la aplicación con GitHub Pages. La disponibilidad de Pages para este repositorio privado depende del plan y la configuración de GitHub. Antes de activar la publicación, confirmar que el sitio tendrá el nivel de acceso adecuado.

## Próximos pasos

- Incorporar el prototipo actual como `index.html`.
- Verificar interacciones y diseño desde Pages.
- Definir la arquitectura de adaptadores de datos para permitir futuras fuentes como CSV/Excel y Odoo.
