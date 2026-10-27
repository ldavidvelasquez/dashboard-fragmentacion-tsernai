# Fragmentación del hábitat idóneo de *Thryophilus sernai* (1986–2024)

Dashboard web con los valores anuales observados de las métricas de fragmentación del hábitat idóneo de *Thryophilus sernai*, calculadas con Makurhini (salidas S22: todos los parches, `min_node_area` = 1 ha, `edge_distance` = 0).

**Ver el dashboard:** https://ldavidvelasquez.github.io/dashboard-fragmentacion-tsernai/

## Contenido

| Pestaña | Hoja del Excel | Qué muestra |
|---|---|---|
| 01 · Métricas anuales | `metricas_anuales` | Serie temporal de área total, número de parches, tamaño medio, MESH, parches < 1 ha y % de área en parches < 1 ha |
| 02 · Resumen Makurhini | `resumen_makurhini` | Métricas reportadas por `MK_Fragmentation()` para cada año |
| 03 · Parámetros | `parametros` | Parámetros con los que se calcularon las métricas |

Solo se presentan valores observados; no incluye modelos ni análisis estadísticos.

## Datos

- [`data/metricas_fragmentacion_S22.xlsx`](data/metricas_fragmentacion_S22.xlsx): archivo original.
- [`data/metricas_anuales.csv`](data/metricas_anuales.csv), [`data/resumen_makurhini.csv`](data/resumen_makurhini.csv), [`data/parametros.csv`](data/parametros.csv): hojas exportadas a CSV.
- `data/datos.js`: los mismos datos en el formato que lee el dashboard.

Colores basados en la leyenda de coberturas y usos del suelo de MapBiomas.
