 ---
layout: page
title: Vectores
nav_order: 2
parent: Sistema Atlas

---
 
MCVP - Módulo de Codificación Vectorial Perceptual

#### Definición

Los **vectores** son entidades estructuradas que representan cuantitativamente los parámetros estéticos extraídos por los sensores a partir de una imagen. Actúan como **unidades de codificación semántico-perceptual**, cuya función es traducir los datos sensoriales en una forma que pueda ser utilizada por los efectores del sistema Atlas para la generación léxica posterior.

Cada vector contiene una **clave semántica** (nombre), un **valor específico** y un **nivel de intensidad**. Estos elementos permiten establecer correlaciones con respuestas estéticas organizadas en la base de datos de efectores.

#### Estructura

Un vector se define mediante los siguientes campos:

- `nombre`: Identificador semántico del parámetro perceptual (por ejemplo: `color_dominante`, `contraste`, `composición_simétrica`).
- `valor`: Categoría o resultado obtenido del análisis de la imagen (por ejemplo: `azul`, `alto`, `asimétrica`).
- `intensidad`: Peso o grado de presencia de ese parámetro en la imagen, expresado como un valor numérico entre 0.0 y 1.0.

#### Ejemplo de vector en formato JSON

json
{
  "nombre": "color_dominante",
  "valor": "azul",
  "intensidad": 0.85
}


#### Función dentro del sistema

Los vectores constituyen la salida directa del MCVP, y funcionan como interfaz entre los sensores (ICP) y los módulos generativos del lenguaje (GLA). Su misión principal es codificar el "ADN perceptual" de la imagen para permitir su transformación en unidades simbólicas (efectores) y finalmente en discurso.

Además, los vectores cumplen funciones de:

Normalización estética: permiten comparar imágenes bajo un mismo marco semántico.

Correlación estructural: habilitan la conexión con efectores a través de reglas definidas en una base de datos.

Ponderación del impacto estético: gracias a la intensidad, determinan qué parámetros tienen mayor influencia en la generación léxica.

##### Consideraciones
Los vectores son independientes del contenido específico de la imagen, y no contienen metadatos, etiquetas o información referencial externa.

El sistema puede generar múltiples vectores por imagen, y su conjunto total define el "perfil perceptual" de la misma.

---
