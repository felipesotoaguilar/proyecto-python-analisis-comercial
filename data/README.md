# Datos

Los archivos de datos **no se incluyen en este repositorio**: pertenecen al material del curso de Python de IPS DATAX.
Son datos ficticios, creados con errores intencionales para practicar limpieza.

Para ejecutar el cuaderno se necesitan estos 6 archivos Excel en una misma carpeta (cada uno con una hoja llamada `Datos`):

| Archivo | Contenido | Registros después de quitar duplicados |
|---|---|---|
| `01_ventas.xlsx` | Ventas (fecha, cliente, producto, vendedor, sucursal, canal, método de pago, cantidad, precio, descuento, total) | 1.800 |
| `02_clientes.xlsx` | Clientes (nombre, país, ciudad, segmento, estado) | 400 |
| `03_productos.xlsx` | Productos (nombre, categoría, marca, costo, precio de lista, estado) | 120 |
| `04_vendedores.xlsx` | Vendedores (nombre, sucursal, nivel, estado) | 30 |
| `05_sucursales.xlsx` | Sucursales (país, ciudad, zona, estado) | 12 |
| `06_metas.xlsx` | Metas mensuales de ventas y unidades por sucursal | 192 |

El cuaderno crea por sí mismo las carpetas `datos_limpios/` y `graficos/` y los archivos finales
(`base_analitica_final.xlsx`, `base_analitica_transformada.xlsx` y `reporte_final_analisis_comercial.xlsx`).
Ninguno de ellos se sube al repositorio (ver `.gitignore`).
