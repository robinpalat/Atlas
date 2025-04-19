
# Sistema Atlas

### 2.1 Descripción General

El **Sistema Atlas** es un sistema generativo de lenguaje y estética que transforma entradas perceptuales (imágenes) en salidas lingüísticas estructuradas, mediante una secuencia organizada de módulos funcionales. Su arquitectura se basa en un flujo de datos compuesto por tres capas fundamentales: **sensores**, **vectores** y **efectores**, que interactúan en un recorrido semántico y estético, culminando en la generación de texto.

El proceso se organiza en tres módulos principales:

- **ICP (Input de Carga Perceptual)**: Captura la información visual cruda y extrae parámetros estéticos.
- **MCVP (Módulo de Codificación Vectorial Perceptual)**: Vectoriza los datos del ICP, estableciendo correlaciones estructurales.
- **GLA (Generador Léxico Atlas)**: Compuesto por el Dispositivo Léxico Dinámico (DLD) y la Fase de Alineamiento Estético (FAE), transforma los vectores en lenguaje y discurso estético.

### 2.2 Diagrama Conceptual

Imagen (Input) ↓ ICP - Sensores ↓ MCVP - Vectores ↓ GLA (DLD + FAE) - Efectores ↓ Texto Final (Output)


### 2.3 Módulos Funcionales

#### 2.3.1 ICP - Input de Carga Perceptual

Es el módulo inicial que recibe la imagen como entrada. Contiene los **sensores**, algoritmos especializados para analizar la estética visual, incluyendo:

- Detección de proporciones áureas y simetrías.
- Análisis de color (dominancia, contraste, equilibrio cromático).
- Distribución espacial de elementos.
- Niveles de complejidad y orden.

Su salida es un conjunto de datos perceptuales estéticos que constituyen el **ADN estético** de la imagen.

#### 2.3.2 MCVP - Módulo de Codificación Vectorial Perceptual

Este módulo interpreta los datos del ICP y los transforma en **vectores semánticos** que representan rasgos, relaciones y dinámicas perceptuales:

- Abstracción de proporciones.
- Representación numérica de tensiones visuales.
- Modelado de patrones y estructuras.

Estos vectores tienen la capacidad de **activar** efectores en la etapa posterior, sirviendo como base estructural del lenguaje.

#### 2.3.3 GLA - Generador Léxico Atlas

Compuesto por dos submódulos:

- **Dispositivo Léxico Dinámico (DLD)**: Contiene un conjunto jerarquizado de **efectores** (léxicos, estéticos, gramaticales), organizados en capas que responden directamente a los vectores activadores.
- **Fase de Alineamiento Estético (FAE)**: Se encarga de **ensamblar el texto final**, organizando los efectores seleccionados en una secuencia coherente, estética y significativa. Aquí interviene la **gramática como coordenada** y puede participar la **taxonomía** como principio regulador o compositivo.

### 2.4 Taxonomía como Módulo Transversal

La **taxonomía** puede intervenir transversalmente en diferentes capas del sistema:

1. **Como efector propiamente dicho**, capaz de producir categorías o niveles conceptuales.
2. **Como jerarquizador de efectores**, actuando como un dispositivo regulador o facilitador de combinaciones.
3. **Como mecanismo compositivo o de masterización**, actuando junto a la gramática para organizar el texto final de forma estética y jerarquizada.

### 2.5 Flujo de Datos

La arquitectura se sostiene sobre un flujo lineal y semántico de datos:

```text
Sensores (ICP) → Vectores (MCVP) → Efectores (GLA) → Texto Final (FAE)
```

Cada módulo está diseñado para ser modular, independiente y expandible, permitiendo múltiples enfoques de análisis, correlación y generación estética.



