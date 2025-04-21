---
layout: default
title: Sistema Atlas
permalink: /
nav_order: 1

---

# Atlas: Sistema de Generación de Texto por Lexoplasticidad
<br><br>

## 2.1 Descripción General

Definición
El Sistema de Generación de Texto por Lexoplasticidad es un modelo conceptual y operativo que produce construcciones textuales a partir de la manipulación estética, estructural y sensorial del léxico, entendido no solo como portador de significados, sino como materia plástica susceptible de transformación creativa.

Fundamento
Este sistema parte del reconocimiento de que, si bien el léxico dentro del lenguaje cumple una función comunicativa sujeta a normas y convenciones, puede ser abstraído de ese marco funcional para ser tratado como material moldeable. A esta capacidad se la denomina lexoplasticidad: la facultad del léxico de asumir nuevas formas estructurales, fónicas o visuales, desligadas o no de su significado tradicional, en función de una intención expresiva, estética o conceptual.

Objetivo
El propósito principal del sistema es generar texto, no solo como medio de comunicación, sino como artefacto estético, resultado de una reconfiguración del léxico orientada por variables perceptuales, estéticas o sensoriales. Se privilegia la forma, la atmósfera, la textura lingüística y el impacto afectivo, antes que la claridad semántica o la función referencial clásica.



## Lexoplasticidad: Definición y Concepto

La lexoplasticidad se refiere a la capacidad del léxico, entendido como un conjunto de palabras y expresiones, para ser moldeado y transformado de manera flexible y dinámica fuera de los marcos rígidos establecidos por la semántica y la gramática tradicionales. A diferencia de su función habitual, que está asociada a la transmisión de significados fijos y estandarizados, la lexoplasticidad implica una visión del léxico como una materia maleable, capaz de adaptarse y evolucionar para generar nuevas formas expresivas, artísticas y creativas.

## Concepto Básico

El concepto de lexoplasticidad parte de la premisa de que el léxico, generalmente considerado un componente rígido dentro del lenguaje, puede ser liberado de su función exclusivamente semántica para convertirse en una herramienta plástica, capaz de ser moldeada de manera artística o conceptual. En este sentido, la lexoplasticidad no está atada a la necesidad de comunicación inmediata o al uso funcional del lenguaje, sino que está enfocada en la transformación estética y experimental del mismo.


##Arquitectura

### 2.2 flujo de datos


La arquitectura se sostiene sobre un flujo lineal de datos:

```text
Vectores primarios (ICP) → Vectores secundarios (MTV) → Efectores (GLA) → Texto
```

El sistema está diseñado para operar con tres tipos de datos: **sensores, vectores y efectores**. Los **sensores** representan datos dinámicos que se extraen directamente de la imagen de entrada. Estos datos son fundamentales para captar las características estéticas de la imagen, tales como las proporciones áureas, la distribución de colores dominantes y secundarios, entre otros parámetros visuales. Los sensores permiten traducir las propiedades visuales de la imagen en información utilizable por el sistema, sirviendo como el primer paso en el flujo de datos. Los **vectores y efectores** son estáticos y   están estructurados de manera modular, independiente y expandible, lo que permite una mayor flexibilidad y sensibilidad al sistema. Esta arquitectura facilita la integración de nuevos componentes y la evolución del sistema a medida que se requiera mayor complejidad o capacidad de respuesta.
<br><br>
### 2.3 Módulos Funcionales

### 2.3.1 ICP - Input de Carga Perceptual

Es el módulo inicial que recibe la imagen como entrada. Contiene los **sensores**, algoritmos especializados para analizar  e interpretar la estética visual, incluyendo:

- Detección de proporciones áureas y simetrías.
- Análisis de color (dominancia, contraste, equilibrio cromático).
- Distribución espacial de elementos.
- Niveles de complejidad y orden.

Su salida es un conjunto de datos perceptuales que constituyen el **ADN estético** de la imagen.
<br><br>
### 2.3.2 MTV - Módulo de Transducción Vectorial

Este módulo interpreta los datos del ICP y los transforma en **vectores** que representan rasgos, relaciones y dinámicas perceptuales:

- Abstracción de proporciones.
- Representación numérica de tensiones visuales.
- Modelado de patrones y estructuras.

Estos vectores tienen la capacidad de **activar** efectores en la etapa posterior, sirviendo como base estructural del lenguaje.
<br><br>
### 2.3.3 GLA - Generador

Compuesto por dos submódulos:


- **Dispositivo Léxico Dinámico (DLD)**: Contiene un conjunto jerarquizado de **efectores** (léxicos, estéticos, gramaticales), organizados en capas que responden directamente a los vectores activadores.


- **Módulo de composición**: Se encarga de **ensamblar el texto final**, en una secuencia coherente, estéticamente significativa. Aquí interviene la **gramática como coordenada** y puede participar la **taxonomía** como principio regulador o compositivo.


---
