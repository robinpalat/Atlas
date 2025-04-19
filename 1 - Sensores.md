---
layout: page
title: Sensores
nav_order: 1
parent: Sistema Atlas

---

ICP - Input de Carga  Perceptual

En el contexto del **Sistema Atlas**, se denomina **Sensores** al conjunto de técnicas computacionales destinadas a la **extracción y cuantificación de parámetros visuales** a partir de una imagen. Su objetivo es registrar datos objetivos que describen la estructura estética del estímulo visual, conformando la **base perceptual primaria** del sistema.

### Función

Los sensores operan como capa de percepción artificial. Constituyen el primer nivel funcional del sistema, denominado **Módulo de Captura Perceptual (ICP)**. Se encargan de identificar, medir y codificar atributos visuales relevantes para la posterior vectorización semántica.

### Características

- **No interpretan significado**, solo detectan patrones medibles.
    
- **Producen datos crudos estructurados**, destinados al MCVP.
    
- Son **técnicamente independientes del lenguaje**, aunque esenciales para su activación.
    

### Ejemplos de sensores implementables

1. **Sensor de proporciones**
    
    - Detecta estructuras geométricas de tipo proporción áurea o simetría fractal.
        
    - Algoritmos utilizados: análisis de relaciones espaciales, bounding boxes y ratios.
        
2. **Sensor de color dominante y secundarios**
    
    - Calcula la distribución porcentual de los colores presentes en la imagen.
        
    - Herramientas: clustering de color (k-means), histogramas HSV/CIELAB.
        
3. **Sensor de granularidad y textura**
    
    - Determina el nivel de detalle superficial mediante análisis frecuencial o convolucional.
        
    - Técnicas: transformadas de Fourier, redes convolucionales entrenadas, Gabor filters.
        
4. **Sensor de contraste global y local**
    
    - Mide el grado de diferenciación tonal o cromática en distintas regiones de la imagen.
        
    - Método: análisis de histograma, diferencia de luminancia relativa.
        
5. **Sensor de orientación y composición**
    
    - Extrae la estructura visual global: centrado, dirección de líneas, peso compositivo.
        
    - Algoritmos: detección de bordes (Canny, Sobel), análisis vectorial de dirección.
        

### Formato de salida

Los sensores producen una salida estructurada y estandarizada en un archivo JSON, conteniendo los parámetros cuantificados:

json

CopiarEditar

`{   "proporcion_aurea": true,   "color_dominante": {"valor": "azul", "porcentaje": 0.80},   "color_secundario": {"valor": "gris", "porcentaje": 0.15},   "textura": "suave",   "simetria_horizontal": 0.92 }`

---

### Rol en el Sistema Atlas

Los **Sensores** son la única fuente de entrada de información al sistema. Actúan como intermediarios entre el estímulo visual y la construcción semántico-estética. Los datos extraídos definen el _input técnico perceptual_, que será transformado por los siguientes módulos del sistema.

---
