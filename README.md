# Prototipo – Sistema de Inventario y Ventas para Botillería

Prototipo de la interfaz (HTML, CSS y Bootstrap) de un sistema de inventario y ventas para una botillería pequeña. El sistema automatiza el control de stock mediante lectura de código de barras y simplifica la operación diaria de los cajeros y del encargado (productos, compras, ventas y reportes básicos).

- **Asignatura:** Proyecto Integrado – TIHI43 (Primavera 2026)
- **Docente:** Valery Rodríguez Castillo
- **Entrega final:** domingo 18-10-2026, 23:59

## Integrantes

| Nombre completo | Usuario de GitHub | Rama |
|---|---|---|
| Angel Astorga | `@usuario-angel` | `feature/aastorga` |
| Kinerett Castillo | `@usuario-kinerett` | `feature/kcastillo` |

## Framework de estilos

Bootstrap 5

## Tabla de gestores

El sistema tiene 24 historias de usuario (HU), agrupadas en 6 gestores según el elemento del sistema que tratan (una por épica del informe). El reparto es de 12 HU por integrante.

| Gestor | HU incluidas | N° de HU | Responsable | Rama |
|---|---|---|---|---|
| Gestor de Acceso | HU-22 a HU-23 | 2 | Angel Astorga | `feature/aastorga` |
| Gestor de Inventario | HU-07, HU-08, HU-10 a HU-12 | 5 | Angel Astorga | `feature/aastorga` |
| Gestor de Proveedores y Compras | HU-19 a HU-21 | 3 | Angel Astorga | `feature/aastorga` |
| Gestor de Reportes | HU-24 a HU-25 | 2 | Angel Astorga | `feature/aastorga` |
| Gestor de Productos | HU-01 a HU-06 | 6 | Kinerett Castillo | `feature/kcastillo` |
| Gestor de Ventas | HU-13 a HU-18 | 6 | Kinerett Castillo | `feature/kcastillo` |

**Nota sobre la complejidad:** el Gestor de Ventas es el más complejo (escaneo, total, confirmación de edad para alcohol, comprobante). Se compensa con que Angel tiene a cargo cuatro gestores.

## Flujo de trabajo

- `main`: versión estable. Solo recibe cambios desde `develop` mediante Pull Request.
- `develop`: rama de integración y pruebas.
- `feature/<inicial><apellido>`: rama personal de cada integrante, creada desde `develop`.

No se hacen commits directos en `main` ni en `develop`. Los commits siguen el formato `tipo(HU-XX): descripción`.
