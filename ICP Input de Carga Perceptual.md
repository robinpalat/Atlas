---
layout: page
title: Input de Carga Perceptual
nav_order: 2

---

# Input de Carga Perceptual

El **ICP (Input de Carga Perceptual)** es el primer módulo del sistema, encargado de recibir y analizar la imagen de entrada para extraer parámetros estéticos clave. Funciona como un conjunto de **sensores** que capturan diversas características visuales de la imagen.

#### Funciones Principales del ICP

1. **Captura de Parámetros Estéticos**: 
   - Detección de **proporciones áureas** y otros patrones geométricos significativos.
   - Análisis del **color dominante** y los colores secundarios en función de su porcentaje en la imagen.
   - Identificación de **contrastaciones visuales** (alta/baja, complementarios, etc.).
   - Cálculo de la **distribución espacial** de los elementos dentro de la imagen (simetría, equilibrio).
   - Evaluación de la **complejidad visual** (número de elementos, formas, repeticiones, etc.).

2. **Generación de ADN Estético**: 
   La salida del ICP es el conjunto de **vectores perceptuales** que sirven de base para el siguiente módulo (MCVP). Estos vectores pueden incluir información sobre el color, la forma, la textura, la distribución de la imagen, etc.

#### Tecnologías y Algoritmos Utilizados

- Algoritmos de procesamiento de imágenes como **OpenCV** para detección de formas y patrones.
- Técnicas de análisis cromático basadas en **modelos de color** como RGB, HSL, o el modelo de **proporción cromática**.
- Algoritmos estadísticos para la identificación de estructuras complejas o patrones de repetición visual.

---
