# Evaluación 1 — Calidad y Preparación de Datos

## Integrantes del grupo

| Nombre                 | Correo                                                                                  |
| ---------------------- | --------------------------------------------------------------------------------------- |
| Alexis Palacios Toledo | [alexis.palacios2301@alumnos.ubiobio.cl](mailto:alexis.palacios2301@alumnos.ubiobio.cl) |
| Benjamín Isla Pino     | [benjamin.isla2301@alumnos.ubiobio.cl](mailto:benjamin.isla2301@alumnos.ubiobio.cl)     |
| Jorge Tuschner Salazar | [jorge.tuschner2301@alumnos.ubiobio.cl](mailto:jorge.tuschner2301@alumnos.ubiobio.cl)   |
| Sebastián Isla Pino    | [sebastian.isla2301@alumnos.ubiobio.cl](mailto:sebastian.isla2301@alumnos.ubiobio.cl)   |

## Descripción del trabajo

En este repositorio se encuentra el desarrollo de la Evaluación 1 de Calidad y Preparación de Datos. El objetivo principal del trabajo es analizar un dataset de rendimiento académico de estudiantes, identificar problemas en la calidad de los datos y aplicar diferentes técnicas para dejarlos preparados para su posterior análisis.

Para realizar el trabajo utilizamos un proceso de Análisis Exploratorio de Datos (EDA), con el cual pudimos conocer mejor las características del dataset, revisar sus variables y detectar situaciones como valores faltantes, registros duplicados, datos fuera de rango, inconsistencias en algunas variables y valores atípicos.

Además, se plantearon y respondieron 4 preguntas de investigación, utilizando gráficos y medidas estadísticas para poder analizar las relaciones existentes entre las variables y la variable objetivo `FinalGrade`.

Una parte importante del trabajo fue el proceso de limpieza y transformación de los datos. Para esto se utilizaron herramientas de `scikit-learn`, principalmente `SimpleImputer`, `OneHotEncoder`, `StandardScaler`, `ColumnTransformer` y `Pipeline`. También se implementó un transformador personalizado llamado `IQRCapper` para trabajar con los valores atípicos que correspondía tratar.

Finalmente, se generó un nuevo dataset llamado `rendimiento_academico_limpio.csv`, el cual corresponde a los datos después del proceso de limpieza y preparación. También se realizó una comparación entre el dataset original y el dataset tratado para comprobar los cambios realizados y verificar la calidad de los datos obtenidos.
