# SoftVet

SoftVet es una plataforma integral para la operación diaria de clínicas veterinarias. Reúne pacientes, expedientes, agendas, ventas, inventario, caja y análisis financiero en una misma aplicación.

Este repositorio aloja las versiones publicadas de la **aplicación instalada para Windows**. Las notas completas también pueden consultarse desde [Versiones y novedades](https://soft-vet-beta.vercel.app/versions).

## Funcionalidades principales

### Pacientes y propietarios

- Expediente individual por mascota con datos generales, fotografía y estado vital.
- Cambio rápido entre las mascotas de un mismo propietario.
- Teléfono principal de acceso y teléfono secundario de contacto.
- Búsqueda por mascota, propietario o teléfono.
- Cuenta del propietario con cargos, pagos, adeudos y saldo a favor.

### Expediente clínico

- Consultas, recetas, vacunas, desparasitaciones, estudios y procedimientos.
- Solicitudes clínicas originadas desde el punto de venta.
- Corrección auditada de información clínica sin modificar cobros ni inventario.
- Historial de cambios y responsables.
- Impresión de documentos clínicos preparados para entregar al propietario.

### Agendas

- Agenda clínica y agenda de estética.
- Citas para mascotas registradas o clientes libres.
- Duración configurable, responsables, notas y estados operativos.
- Acceso directo al expediente y al cobro desde las citas.

### Punto de venta, cuentas y caja

- Venta libre o asociada a propietario y mascota.
- Productos, conceptos libres, procedimientos y estudios.
- Pagos en efectivo, tarjeta, transferencia u otros métodos.
- Pagos parciales, aplicación de saldo a favor y cobro de adeudos anteriores.
- Confirmaciones seguras para evitar ventas o pagos duplicados ante reintentos.
- Cajas, sesiones, cortes, entradas, salidas, devoluciones y comprobantes.

### Inventario

- Productos organizados por categoría, familia y tipo.
- Control por lotes, proveedor, caducidad, costo y presentación.
- Venta por unidad base o empaque completo.
- Inventario interno por áreas y transferencia de existencias.
- Cuarentena, mermas y trazabilidad de movimientos.

### Contabilidad y análisis

- Movimientos diarios y cortes por caja.
- Dashboard por día, semana o mes.
- Ingresos separados entre productos, clínica, estética y otros conceptos.
- Anticipos, descuentos, devoluciones, salidas, afluencia y productos más vendidos.
- Exportación e impresión de reportes financieros y movimientos mensuales.

### Personal y seguridad

- Múltiples clínicas y membresías por usuario.
- Roles y permisos delegables por módulo y acción.
- Cédula profesional por clínica.
- Autorizaciones para acciones sensibles.
- Auditoría de cambios clínicos y operaciones financieras.

## Aplicación instalada

La versión para Windows añade integración local para:

- Impresión directa de tickets y documentos.
- Selección de impresoras por función.
- Actualizaciones automáticas o manuales.
- Zoom de interfaz mediante Ajustes o atajos de teclado.
- Permanencia opcional en la bandeja del sistema.
- Corrección ortográfica y menú contextual nativo.

## Descargar e instalar

1. Abre la sección [Releases](https://github.com/Dekstro999/SoftVet-Dekstop/releases).
2. En la versión más reciente descarga **`SoftVet-Setup-x.y.z.exe`** para realizar una instalación normal.
3. Ejecuta el instalador y elige la carpeta de destino cuando se solicite.

También se publica **`SoftVet-x.y.z.exe`** como versión portable. Los archivos `latest.yml` y `.blockmap` son utilizados por el actualizador automático y no necesitan descargarse manualmente.

## Versiones y novedades

Cada release incluye notas separadas por tipo:

- **ADD:** funciones nuevas.
- **MOD:** mejoras o cambios de comportamiento.
- **FIX / BUG:** correcciones de funciones ya publicadas.
- **DEL:** funciones retiradas.

El historial se sincroniza con SoftVet y puede consultarse sin iniciar sesión en [soft-vet-beta.vercel.app/versions](https://soft-vet-beta.vercel.app/versions).

## Acceso web

SoftVet también está disponible desde el navegador en [soft-vet-beta.vercel.app](https://soft-vet-beta.vercel.app/).
