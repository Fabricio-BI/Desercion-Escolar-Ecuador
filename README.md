# Análisis de Deserción Escolar en Ecuador

## Descripción
Este proyecto analiza la deserción escolar en Ecuador entre los años 2014 y 2023. Se examinan tendencias a lo largo del tiempo, diferencias según Zona, Sostenimiento, Área y Régimen Escolar, así como la relación entre pobreza y abandono escolar. Además, se identifican las provincias más afectadas en el último periodo lectivo y se evalúa la correlación entre pobreza y deserción escolar.

## Preguntas de Investigación
- ¿Cómo ha evolucionado la deserción escolar en Ecuador entre 2014 y 2023?
- ¿Se puede observar algún patrón en las variables Zona, Sostenimiento, Área y Régimen Escolar para el periodo lectivo 2023-2024?
- ¿Cuáles son las provincias más afectadas por la deserción escolar en el último periodo lectivo?
- ¿Las provincias con las tasas de deserción más altas son las que tienen mayores índices de pobreza?
- ¿Existe alguna correlación entre pobreza y deserción escolar?

## Datos Utilizados
El proyecto se basa en datos estructurados en cuatro carpetas principales:

- **Datos Crudos**: Contiene los datos originales sin procesar.
- **Datos Procesados**: Incluye los datos limpios y estructurados para el análisis.
- **Script_Limpieza_Datos**: Contiene los scripts en Python utilizados para la limpieza y transformación de los datos.
- **Shapefile_Ecuador**: Archivos geoespaciales utilizados para la visualización de datos en mapas.

## Análisis Exploratorio
El análisis principal fue realizado en el cuaderno **Eda_Escolar**, donde se examinan las tendencias de desercón escolar y sus posibles causas.

## Principales Hallazgos
- La tasa de abandono escolar mostró una tendencia a la baja hasta 2019-2020, pero repuntó significativamente en 2021-2022, posiblemente debido a la pandemia de COVID-19.
- Las zonas 6, 1 y 3 presentan las tasas más altas de deserción, lo que indica desafíos en acceso y permanencia educativa.
- Existe una correlación positiva moderada-alta (0.65) entre pobreza y deserción escolar, sugiriendo que la situación económica es un factor determinante en la continuidad educativa.
- La desercón escolar es mayor en el área rural (1.95%) en comparación con la urbana (1.90%), aunque la diferencia es leve.
- En el régimen Sierra, la tasa de deserción es más alta (2.02%) que en la Costa (1.83%), posiblemente debido a la necesidad de los estudiantes de trabajar en actividades agrícolas.
- Las provincias con mayor deserción escolar se concentran en la región Amazónica y Costera, destacando Morona Santiago (5.42%) y Sucumbíos (3.57%).
- Las provincias con mayor deserción escolar coinciden en gran medida con las de mayores índices de pobreza, lo que sugiere una relación directa entre ambas variables.

## Tecnologías Utilizadas
- **Python**: Análisis de datos con Pandas,Geopandas, Matplotlib y Seaborn.
- **Jupyter Notebook**: Desarrollo de análisis exploratorio.
-

## Estructura del Proyecto
```
📂 Analisis_Desercion_Escolar
│── 📂 Datos_Crudos
│── 📂 Datos_Procesados
│── 📂 Script_Limpieza_Datos
│── 📂 Shapefile_Ecuador
│── 📂 Eda_Escolar.ipynb
│── README.md
```



## Autor
[Fabricio Coque Marin](https://www.linkedin.com/in/fabricio-coque-marin/)
