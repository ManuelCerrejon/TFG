# Descripción del Repositorio
Este repositorio contiene el código fuente y los recursos necesarios para replicar y ampliar los experimentos presentados en la competición DETESTS 2024, que se centra en la detección de estereotipos sociales en textos en español. El objetivo de la competición es promover el desarrollo de tecnologías de procesamiento del lenguaje natural (PLN) que puedan identificar y clasificar automáticamente estereotipos en diversos contextos textuales, contribuyendo así a una comunicación en línea más inclusiva y respetuosa. Este repositorio incluye modelos, scripts de preprocesamiento, ensembler, datos de entrenamiento y evaluación, así como instrucciones detalladas para ejecutar y evaluar los experimentos. El trabajo se centra en el empleo de Learning With Desagreement para la resolución de las tareas de la competición.

## Contenido del Repositorio
El repositorio está estructurado en varias carpetas y archivos, cada uno de los cuales juega un papel crucial en el proyecto:

- Task 1 y 2: El repositorio esta dividido en las dos tareas, Task 1 y 2, cada una en su respectiva carpeta. La task 1 se centra en la identificación de estereotipos en textos en español, mientras que la task 2 aborda la detección de estereotipos implícitos y explícitos en diversos contextos textuales.

- Notebooks: Contiene varios Jupyter notebooks que explican detalladamente el proceso de preparación de datos, entrenamiento de modelos y evaluación de resultados. Entre los notebooks destacados se encuentran aquellos que tratan la optimización de conjuntos de entrenamiento, la construcción de modelos basados en transformers como BERT y RoBERTa.

- Enmsemble: Contiene el script utilizado para realizar los ensemble de los modelos obtenidos por anotador.

- Conjuntos de Datos: Contiene los conjuntos de datos utilizados para el entrenamiento y la evaluación de los modelos, así como scripts para su preprocesamiento.

- Predicciones: Carpeta donde se almacenan las predicciones de los diferentes modelos.
