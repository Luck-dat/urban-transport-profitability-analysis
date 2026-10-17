# Análisis de Rentabilidad - Transporte Urbano

Proyecto de análisis de datos para evaluar y optimizar la rentabilidad operativa en la flota de transporte de la empresa "La Granburu", enfocado en el consumo de combustible y la distribución de la demanda.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luck-dat/urban-transport-profitability-analysis/blob/main/transport_profitability_analysis.ipynb)

## Preguntas clave del proyecto

- ¿Cuál es la recaudación total y cómo se distribuye por unidad?
- ¿Qué internos son los más y menos eficientes en pesos recaudados por litro de gasoil?
- ¿Cuáles son las franjas horarias de mayor demanda (horas pico)?
- ¿Hay diferencias significativas de consumo entre unidades nuevas y antiguas?

## Resultados principales

- Las unidades de la serie 100 (más antiguas) consumen **20.7% más gasoil** que las de la serie 200 (94.99 vs. 78.68 L/día), lo que se traduce en un consumo específico de **38.54 L/100 km vs. 31.50 L/100 km** frente a un benchmark de 30–40 L/100 km para buses urbanos.
- La unidad **204** resultó la más rentable del período; la **104** la menos rentable.
- Priorizar las 3 unidades más rentables (201, 204, 205) mejora la ganancia promedio por unidad en **$192.238** (+4.46%).
- La demanda cae **~49% los fines de semana** respecto a días hábiles, lo que sugiere ajustar la frecuencia en esos días.

## Tecnologías

- Python (Pandas, NumPy, Matplotlib)
- Google Colab

## Ejecución

Podés abrir y correr el notebook directamente en Colab usando el badge de arriba, o clonar el repositorio y abrir `transport_profitability_analysis.ipynb` en cualquier entorno con Jupyter.

## Nota

Los datos utilizados son **simulados con fines demostrativos**, con parámetros calibrados a valores realistas de la operación de un bus urbano (precio de gasoil, tarifas SUBE, kilometraje diario). Ver la sección "Limitaciones y supuestos" dentro del notebook para más detalle.
