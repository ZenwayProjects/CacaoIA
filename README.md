# Algoritmo de Detección de Madurez del Cacao

Este repositorio contiene la implementación de un algoritmo de detección de madurez del cacao utilizando un modelo de aprendizaje profundo. El algoritmo toma imágenes de cacao como entrada y predice sus niveles de madurez. El modelo está diseñado para clasificar las imágenes de cacao en diferentes categorías: cocoaI, cocoaM, cocoaS y notcocoa.

## Tabla de Contenidos

- [Introducción](#introducción)
- [Conjunto de Datos](#conjunto-de-datos)
- [Arquitectura del Modelo](#arquitectura-del-modelo)
- [Preprocesamiento de Datos](#preprocesamiento-de-datos)
- [Entrenamiento](#entrenamiento)
- [Evaluación](#evaluación)
- [Uso](#uso)

## Introducción

La detección de la madurez del cacao es un aspecto importante en la producción de cacao. Este algoritmo aprovecha técnicas de aprendizaje profundo para clasificar automáticamente las imágenes de cacao en diferentes niveles de madurez, lo que puede ayudar a los agricultores y expertos a evaluar el estado de las vainas de cacao.

## Conjunto de Datos

El conjunto de datos utilizado para el entrenamiento y la evaluación está disponible en el directorio `dataset_cacao`. Consiste en imágenes categorizadas en conjuntos de entrenamiento y prueba. El conjunto de datos incluye varios niveles de madurez y una clase "notcocoa" para imágenes que no son de cacao.

## Arquitectura del Modelo

La arquitectura del modelo de aprendizaje profundo utilizado para la detección de madurez del cacao es una arquitectura personalizada diseñada para manejar tareas de clasificación de imágenes.

## Preprocesamiento de Datos

Las imágenes se preprocesan utilizando técnicas como el redimensionamiento, la aumentación de datos y la escala de los valores de píxeles.

## Entrenamiento

El modelo se entrena utilizando el conjunto de datos de entrenamiento y se valida utilizando el conjunto de datos de validación.

## Evaluación

El modelo entrenado se evalúa en el conjunto de datos de prueba para evaluar su rendimiento.

## Uso

1. Clona este repositorio:


2. Coloca tus imágenes de cacao en el directorio `dataset_cacao/Testing`. y `dataset_cacao/Training`

4. Ejecuta el script de predicción: Desde el collab para mayor facilidad

## Contribuciones

¡Las contribuciones a este proyecto son bienvenidas! Si encuentras algún problema o tienes sugerencias para mejoras, abre un issue o envía un pull request.



