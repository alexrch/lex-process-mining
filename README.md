# Process Mining · Compras y recepción

Aplicación web estática para explorar procesos de compras y recepción mediante Process Mining.

## Estado actual

- Prototipo web inicial incorporado en `index.html`.
- Datos sintéticos generados en el navegador.
- Mapa de proceso navegable con zoom y desplazamiento.
- Filtros por proveedor, categoría, resultado y periodo.
- Selección de actividades y transiciones para explorar órdenes.
- Variantes de proceso, tiempos entre eventos y cuellos de botella.
- Sin conexión a Odoo ni a fuentes externas todavía.

## Ejecutar localmente

Abre `index.html` en un navegador moderno. La demo estática no requiere instalación ni servidor.

## Datos y privacidad

Los datos actuales son ficticios y se generan en el navegador. No incorpores credenciales, secretos ni datos personales o productivos al repositorio.

## Flujo de cambios

1. Crear una rama por requisito o mejora.
2. Desarrollar y validar el cambio en esa rama.
3. Abrir un Pull Request hacia `main`.
4. Revisar diferencias y probar la aplicación antes de integrar.

Convención de ramas: `tipo/numero-descripcion-corta`, por ejemplo `feat/001-initial-web-app`.

Convención de commits: `tipo(area): descripción`, por ejemplo `feat(graph): improve process map navigation`.

## Publicación

La publicación con GitHub Pages está pendiente de configuración y validación. La disponibilidad de Pages para este repositorio privado depende del plan y la configuración de GitHub; confirma también el nivel de acceso del sitio publicado antes de activarlo.

## Próximos pasos

- Revisar el prototipo desde la rama de trabajo y validar sus interacciones.
- Abrir un Pull Request para integrar la aplicación en `main`.
- Configurar y probar GitHub Pages.
- Diseñar adaptadores de datos para futuras fuentes como CSV/Excel y Odoo.
