---
layout: page
title: 2- Módulo de Transducción Vectorial
nav_order: 2
parent: Módulos
---

# Módulo de Transducción Vectorial
<br>
El **MTV** es el módulo intermedio del Sistema Atlas. Su función principal es **vectorizar** los datos perceptuales generados por el ICP y mapearlos a un formato estructurado de vectores semánticos que representan las características clave de la imagen. Estos vectores sirven para activar los **efectores** en el siguiente paso del sistema.
<br>
#### Funciones del MTV
<br>
1. **Vectorización de Parámetros**:
   - Los datos capturados por el ICP (como el color dominante, proporciones áureas, etc.) son **codificados en vectores numéricos**.
   - La vectorización sigue un **modelo de codificación semántica** donde cada vector corresponde a un parámetro perceptual.
   - Se mapean **atributos estéticos** (por ejemplo, tono, intensidad, saturación, distribución) a valores vectoriales.
<br>
2. **Correlación entre Vectores**:
   - El MTV establece **correlaciones** entre los diferentes vectores perceptuales extraídos de la imagen.
   - Cada vector puede activarse en función de los parámetros contextuales del análisis visual, lo que permite la creación de una **estructura coherente**.
<br>
3. **Generación de Salida**:
   - El MTV genera una **salida estructurada** de vectores que son enviados al siguiente módulo (PLP).
   - Esta salida constituye una base semántica para la traducción en texto o la activación de efectos de estilo.

#### Tecnologías y Algoritmos Utilizados

- **Machine Learning** y **Deep Learning** para el modelado de correlaciones entre vectores.
- Algoritmos de **análisis multidimensional** para la creación de la representación vectorial de los parámetros perceptuales.
- **Redes neuronales artificiales** para la identificación de patrones complejos y correlaciones entre vectores.

---
