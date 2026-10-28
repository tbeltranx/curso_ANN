# Redes Neuronales Artificiales (ANNs)

## Descripción

Curso introductorio y práctico sobre los fundamentos de las **Redes Neuronales Artificiales** (*Artificial Neural Networks*, ANNs) y el flujo de trabajo para desarrollar, entrenar y evaluar modelos iniciales con herramientas de acceso libre.

El contenido comprende los fundamentos de las redes neuronales, las métricas y estrategias de validación, el procesamiento de datos y el desarrollo de un ejercicio práctico en Python mediante Google Colab.

## Objetivo general

Introducir y aplicar los fundamentos de las Redes Neuronales Artificiales (ANNs), así como los aspectos básicos de un flujo de trabajo orientado al entrenamiento de modelos iniciales mediante herramientas de acceso libre.

## Conocimientos previos

- Fundamentos de **aprendizaje automático** (*Machine Learning*).
- Manejo básico o intermedio de **Python**: variables, estructuras de control, funciones, listas y diccionarios.
- Familiaridad con entornos de trabajo como **Jupyter Notebook** o **Google Colab**.

## Contenido del curso

### Módulo 1. Fundamentos de las Redes Neuronales Artificiales (ANNs)

1. Las redes neuronales artificiales dentro de la inteligencia artificial.
2. Concepto de red neuronal artificial.
3. Perceptrón multicapa (*Multilayer Perceptron*, MLP).
4. Arquitecturas de redes neuronales artificiales.
5. Aprendizaje por retropropagación (*backpropagation*).
6. Hiperparámetros de las ANNs.
7. Funciones de activación.

### Módulo 2. Métricas, validación y sobreajuste

1. Métricas de desempeño para regresión.
2. Métricas de desempeño para clasificación.
3. Problemas comunes de ajuste, incluido el sobreajuste.
4. Estrategias de validación.

### Módulo 3. Flujo de trabajo general para el desarrollo de modelos de ANNs

1. Adquisición, limpieza y análisis exploratorio de datos.
2. Ingeniería de variables.
3. Procesamiento de datos y ajuste de hiperparámetros.
4. Entrenamiento y validación.
5. Explicabilidad (*Explainable AI*, XAI) e interpretabilidad.
6. Despliegue de modelos.

### Módulo 4. Ejercicio práctico en Google Colab

1. Ecosistema de herramientas en Python.
2. Ejercicio práctico de desarrollo de un modelo de red neuronal artificial.

## Flujo de trabajo de referencia

El curso aborda las siguientes etapas generales para desarrollar un modelo:

```text
Adquisición de datos
       ↓
Limpieza y análisis exploratorio
       ↓
Ingeniería y procesamiento de variables
       ↓
Configuración del modelo y sus hiperparámetros
       ↓
Entrenamiento
       ↓
Validación y evaluación del desempeño
       ↓
Explicabilidad e interpretabilidad
       ↓
Despliegue
```

> Este esquema sintetiza los temas del módulo 3; no representa un procedimiento único ni implica que todas las etapas se implementen en el ejercicio práctico.

## Herramientas y entorno de trabajo

- **Python:** lenguaje de programación utilizado para el trabajo práctico.
- **Google Colab:** entorno para desarrollar y ejecutar el ejercicio práctico.
- **Jupyter Notebook:** entorno alternativo para trabajar con cuadernos de Python.
- **Herramientas de acceso libre:** recursos para el desarrollo y entrenamiento de modelos iniciales.

> El temario no especifica bibliotecas concretas de Python ni versiones de software. Estas podrán documentarse conforme se incorporen los ejercicios al repositorio.

## Resultados de aprendizaje esperados

Al recorrer el contenido del curso, se busca desarrollar la capacidad de:

- Reconocer los componentes y las arquitecturas básicas de una ANN.
- Comprender el perceptrón multicapa, la retropropagación, las funciones de activación y los hiperparámetros.
- Distinguir métricas de evaluación para problemas de regresión y clasificación.
- Identificar problemas de ajuste y aplicar estrategias de validación.
- Organizar un flujo de trabajo para preparar datos, entrenar y validar modelos.
- Reconocer la importancia de la explicabilidad, la interpretabilidad y el despliegue.
- Desarrollar un ejercicio inicial de redes neuronales en Python utilizando Google Colab.

## Organización del repositorio

Los materiales de este repositorio se agrupan de la siguiente manera:

```text
.
├── README.md
├── notebooks/
│   └── ejercicio_practico.ipynb
├── datos/
├── modelos/
└── recursos/
```

- `notebooks/`: cuadernos con ejemplos y ejercicios.
- `datos/`: conjuntos de datos utilizados en las prácticas, cuando su distribución esté permitida.
- `modelos/`: modelos entrenados que se decida conservar.
- `recursos/`: materiales complementarios y referencias técnicas.

## Alcance

El programa está orientado a la **introducción y aplicación de modelos iniciales** de redes neuronales artificiales. Incluye fundamentos conceptuales, evaluación, validación y un ejercicio práctico. No especifica un conjunto de datos, una arquitectura particular para la práctica ni resultados numéricos de entrenamiento.
