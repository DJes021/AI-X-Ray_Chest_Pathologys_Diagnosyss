# AI-X-Ray_Chest_Pathologys_Diagnosyss
Diagnosis de patologías pulmonares, aplicando IA sobre imágenes de rayos X.


Este proyecto aborda la clasificación de imágenes de rayos X utilizando técnicas avanzadas de aprendizaje profundo. A través de este trabajo, se implementará un clasificador de imágenes basado en la arquitectura DenseNet121 mediante el uso de transfer learning. El objetivo principal es diagnosticar patologías pulmonares utilizando un conjunto de datos de rayos X, y se emplean varias técnicas para mejorar el rendimiento del modelo.

## Index

- [1. Import de paquetes y funciones](#1)
- [2. Load the Datasets](#2)
    - [2.1. Proceso de carga de datasets](#2-1)
- [3. Data Development](#3)
    - [3.1. Fuga de datos](#3-1)
    - [3.2. Preparar las imágenes y aplicar data augmentation](#3-2)
    - [3.3. Balance de clases](#3-3)
    - [3.4. Función de pérdida ponderada](#3-4)
- [4. Desarrollo del modelo - DenseNet121](#4)
    - [4.1. Ajuste de hiperparámetros usando libreria Optuma](#4-1)
    - [4.2. Definición de Callbacks y entrenamiento del modelo optimizado](#4-2)
    - [4.3. Guardar y cargar modelo](#4-3)
- [5. Predicción y evaluacion](#5)
    - [5.1. Curva ROC y AUROC](#5-1)
- [6. Productivizar el modelo](#6)
    - [6.1. Visualización de muestras con GradCAM](#6-1)
