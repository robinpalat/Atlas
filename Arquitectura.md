---
layout: page
title: Arquitectura
nav_order: 3
has_children: true

---

## Arquitectura 
<br><br>
### flujo de datos


La arquitectura se sostiene sobre un flujo lineal de datos:

```text
Vectores primarios (ICP) → Vectores secundarios (MTV) → Efectores (GLA) → Texto
```

El sistema está diseñado para operar con tres tipos de datos: **sensores, vectores y efectores**. Los **sensores** representan datos dinámicos que se extraen directamente de la imagen de entrada. Estos datos son fundamentales para captar las características estéticas de la imagen, tales como las proporciones áureas, la distribución de colores dominantes y secundarios, entre otros parámetros visuales. Los sensores permiten traducir las propiedades visuales de la imagen en información utilizable por el sistema, sirviendo como el primer paso en el flujo de datos. Los **vectores y efectores** son estáticos y   están estructurados de manera modular, independiente y expandible, lo que permite una mayor flexibilidad y sensibilidad al sistema. Esta arquitectura facilita la integración de nuevos componentes y la evolución del sistema a medida que se requiera mayor complejidad o capacidad de respuesta.
<br><br>
### Módulos 
<br><br>
### ICP - Input de Carga Perceptual

El ICP es la unidad encargada de captar la imagen de entrada y extraer de ella una serie de parámetros estéticos. Utiliza sensores especializados para leer atributos como:
- Proporciones geométricas (incluyendo proporción áurea)
- Distribución y predominancia de colores
- Simetría
- Contrastes y complejidad visual

Estos parámetros conforman lo que se denomina el *ADN estético* de la imagen. Este output es el insumo bruto del sistema.
<br><br>
### MTV - Módulo de Transducción Vectorial

Este módulo interpreta los datos del ICP y los transforma en **vectores** que representan rasgos, relaciones y dinámicas perceptuales:

- Abstracción de proporciones.
- Representación numérica de tensiones visuales.
- Modelado de patrones y estructuras.

Estos vectores tienen la capacidad de **activar** efectores en la etapa posterior, sirviendo como base estructural del lenguaje.
<br><br>
### PLP – Procesador de Lexoplasticidad

Compuesto por dos submódulos:


- **Dispositivo Léxico Dinámico (DLD)**: Contiene un conjunto jerarquizado de **efectores** (léxicos, estéticos, gramaticales), organizados en capas que responden directamente a los vectores activadores.


- **Módulo de composición**: Se encarga de **ensamblar el texto final**, en una secuencia coherente, estéticamente significativa. Aquí interviene la **gramática como coordenada** y puede participar la **taxonomía** como principio regulador o compositivo.


---
