# Spark Use Case

Este repositorio contiene tres *notebooks* para el preprocesamiento,
modelado y visualización de datos de los **Beneficiarios de Ayuda de la
Política Agrícola Común (PAC) 2024** del [Fondo Español de Garantía
Agraria
(FEGA)](https://www.fega.gob.es/es/datos-abiertos/consulta-de-beneficiarios-pac/descarga-de-ficheros).

## Notebooks

1.  **01_limpieza -- Preprocesamiento de datos PAC**\
    Limpieza y preparación de datos.\
    Fuente: Beneficiarios PAC 2024.

2.  **02_modelo -- Detección de anomalías con KMeans**\
    Ingeniería de variables, entrenamiento de KMeans, cálculo de
    puntuaciones de anomalía (distancia al *cluster*) y generación de un
    dataset enriquecido para publicación en un espacio de datos.\

3.  **03_visualizacion -- Revisión de resultados (opcional)**\
    Revisión preliminar de resultados y generación de visualizaciones
    para la memoria del TFM.

## Ejecución

-   Instalar dependencias con `uv lock` y sincronizar con
    `uv sync`.\
-   Ejecutar en orden (1,2,3)
