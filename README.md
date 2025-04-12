# Recursos Humanos de la CCSS

Este repositorio contiene datos relacionados con la gestión de personal de la **Caja Costarricense de Seguro Social (CCSS)**. El archivo principal es un conjunto de datos en formato CSV que incluye información relevante sobre evaluaciones, puestos y otras variables relacionadas con el recurso humano de la institución.

## Contenido

- `raw-data\`: Continue datasets sin tratamiento ni consolidación. Se pueden obtener directamente y en otros formatos desde  la [página de datos abiertos de la CCSS](ccss.sa.cr/datos-abiertos).
- `clean-data\`: Archivos con los datos tratados para análisis exploratorios y modelos de ciencia de datos relacionados con la gestión de talento humano en la CCSS.

## Descripción de los datos

A continuación, se listan algunas de las columnas presentes en el archivo:

| # |  Column | Non-Null | Count | Dtype  |
| --- | --- | --- | --- | --- |
| 0 | Cedula | 66508 | non-null | object |
| 1 | Calificacion | 55197 | non-null | float64 |
| 2 | Perfil | 0 | non-null | float64 | 
| 3 | Fecha de Actualizacion | 55197 | non-null | object | 
| 4 | Nombre | 1924 | non-null | object |
| 5 | Unidad de procedencia (UP) | 1924 | non-null | float64 |
| 6 | Detalle de UP | 1924 | non-null | object |
| 7 | Fecha de actualización | 1924 | non-null | object | 
| 8 | Salario | 65386 | non-null | object |
| 9 | Puesto | 65386 | non-null | object |
| 10 | Fecha de actualizacion | 65386 | non-null | object |

## Fuente de los datos

Datos obtenidos en 2025 desde la [página de datos abiertos de la CCSS](ccss.sa.cr/datos-abiertos)
