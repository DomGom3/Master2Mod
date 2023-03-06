# Master2Mod
Repositorio creado para el Examen del módulo 2

## Procedimiento Realizado

### Importe de Librerías

Para la realización del ejercicio se utilizaron las librerías: pandas, numpy (para tratamiento de datos), seaborn, matplotlib (para los gráficos), y sklearn (para la aplicación de los modelos)

### Carga de Datos
Se utilizó el dataset de cáncer de mama de la universidad de Wisconsin obtenido de https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29, mismo al que se le añadió la etiqueta de los campos/columnas

### Observación y Preprocesamiento

En el procesamiento de la información se revisa los tipos de datos en el dataset, posteriormente se verifican los registros duplicados, valores nulos y valores inválidos.

Se transformó el campo "Bare_Nuclei" de tipo objeto a tipo int.

Una vez realizada la limpieza de los datos, se realizó la matriz de correlación para poder observar la importancia de las variables para el análisis.

### Modelos

Se aplicó los modelos: k vecinos, árbol de decisión y random forest al dataset. En donde se probó con distintos parámetros de regularización y se seleccionó los mejores en base a los porcentajes de error obtenidos, adicionalmente se realizó  matriz de confusión de cada uno de los modelos concentrándome en la matriz de los datos de testing principalmente en los falsos negativos (ya que estos como se menciona son los más críticos al momento de la valoración de las pacientes). 

### Conclusión
Se observó que el modelo con mejor rendimiento fue el modelo de Random Forest con profundidad de 6, mismo que proporciono la menor cantidad de falsos negativos (2) en comparación al resto de modelos aplicados.  

  
**Realizado por:**  

Doménica Gómez  
Modelos y Aprendizajes  
EIG-UIDE

