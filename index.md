---
layout: default
title: Sistema Atlas
permalink: /
nav_order: 1

---

# Sistema Atlas
<br><br>

### 2.1 Descripción General
<br><br>
El **Sistema Atlas** es un sistema generativo de lenguaje y estética que transforma entradas perceptuales (imágenes) en salidas lingüísticas estructuradas, mediante una secuencia organizada de módulos funcionales. Su arquitectura se basa en un flujo de datos compuesto por tres capas fundamentales: **sensores**, **vectores** y **efectores**, que interactúan culminando en la generación de texto.
<br>
El proceso se organiza en tres módulos principales:

- **ICP (Input de Carga Perceptual)**: Captura la información visual cruda y extrae parámetros estéticos.
- **MCVP (Módulo de Codificación Vectorial Perceptual)**: Vectoriza los datos del ICP, estableciendo correlaciones estructurales.
- **GLA (Generador Léxico Atlas)**: Compuesto por el Dispositivo Léxico Dinámico (DLD) y la Fase de Alineamiento Estético (FAE), transforma los vectores en lenguaje y discurso estético.
<br><br>

### 2.2 flujo de datos


La arquitectura se sostiene sobre un flujo lineal de datos:

```text
Sensores (ICP) → Vectores (MCVP) → Efectores (GLA) → Texto Final (FAE)
```

El sistema está diseñado para operar con tres tipos de datos: **sensores, vectores y efectores**. Los **sensores** representan datos dinámicos que se extraen directamente de la imagen de entrada. Estos datos son fundamentales para captar las características estéticas de la imagen, tales como las proporciones áureas, la distribución de colores dominantes y secundarios, entre otros parámetros visuales. Los sensores permiten traducir las propiedades visuales de la imagen en información utilizable por el sistema, sirviendo como el primer paso en el flujo de datos. Los **vectores y efectores** son estáticos y   están estructurados de manera modular, independiente y expandible, lo que permite una mayor flexibilidad y sensibilidad al sistema. Esta arquitectura facilita la integración de nuevos componentes y la evolución del sistema a medida que se requiera mayor complejidad o capacidad de respuesta.
<br><br>
### 2.3 Módulos Funcionales
<br><br>
### 2.3.1 ICP - Input de Carga Perceptual

Es el módulo inicial que recibe la imagen como entrada. Contiene los **sensores**, algoritmos especializados para analizar  e interpretar la estética visual, incluyendo:

- Detección de proporciones áureas y simetrías.
- Análisis de color (dominancia, contraste, equilibrio cromático).
- Distribución espacial de elementos.
- Niveles de complejidad y orden.

Su salida es un conjunto de datos perceptuales que constituyen el **ADN estético** de la imagen.
<br><br>
### 2.3.2 MCVP - Módulo de Codificación Vectorial Perceptual
<br><br>
Este módulo interpreta los datos del ICP y los transforma en **vectores** que representan rasgos, relaciones y dinámicas perceptuales:

- Abstracción de proporciones.
- Representación numérica de tensiones visuales.
- Modelado de patrones y estructuras.

Estos vectores tienen la capacidad de **activar** efectores en la etapa posterior, sirviendo como base estructural del lenguaje.
<br><br>
### 2.3.3 GLA - Generador Léxico Atlas
<br><br>
Compuesto por dos submódulos:


- **Dispositivo Léxico Dinámico (DLD)**: Contiene un conjunto jerarquizado de **efectores** (léxicos, estéticos, gramaticales), organizados en capas que responden directamente a los vectores activadores.


- **Fase de Alineamiento Estético (FAE)**: Se encarga de **ensamblar el texto final**, en una secuencia coherente, estéticamente significativa. Aquí interviene la **gramática como coordenada** y puede participar la **taxonomía** como principio regulador o compositivo.


---
