---
layout: page
title: Efectores
nav_order: 3
parent: Flujo de Datos del Sistema

---

#### Definición

Los **efectores** son unidades léxicas o estéticas que constituyen la **respuesta simbólica o verbal** activada por la acción de los vectores. Funcionan como **elementos generativos de lenguaje o estructuras estéticas**, siendo el resultado final de la correlación entre la percepción visual (vectores) y el sistema de salida léxica (GLA).

En términos funcionales, los efectores representan **palabras, frases, estilos, tonos o estructuras formales** que se manifiestan en el texto producido como output del sistema.

#### Estructura

Cada efector se compone de los siguientes elementos:

- `nombre`: Título o categoría del efector (por ejemplo: `color_dominante`, `tono_emocional`, `nivel_de_orden`).
- `tipo`: Define la naturaleza del efector (léxico, estético, composicional, gramatical).
- `valor`: Contenido del efector (por ejemplo: `azul`, `melancólico`, `entropía`, `repetición`).
- `peso`: Valor numérico opcional que indica su intensidad o prioridad en la generación del texto.
- `vector_disparador`: Nombre del vector que activa este efector.
- `relación`: Tipo de vínculo con el vector (directo, inverso, contextual).

#### Ejemplo de efector en formato JSON

```json
{
  "nombre": "color_dominante",
  "tipo": "léxico",
  "valor": "azul",
  "peso": 0.85,
  "vector_disparador": "color_dominante",
  "relación": "directa"
}

```

#### Función dentro del sistema

Los efectores constituyen la salida principal del Dispositivo Léxico Dinámico (DLD), y junto con la Fase de Alineamiento Estético (FAE), forman el Generador Léxico Atlas (GLA). Su función es traducir los vectores en lenguaje humano o estructuras simbólicas perceptibles, generando así el texto final.

Cumplen además los siguientes roles:

- Actuar como puentes semánticos entre percepción visual y lenguaje.

- Encarnar decisiones estéticas basadas en correlaciones con vectores perceptuales.

- Estructurar el discurso generado, permitiendo estilos expresivos, tonos emocionales y otras características textuales.

##### Clases funcionales de efectores

- Efectores léxicos: palabras o frases asociadas directamente a valores perceptuales.

- Efectores estilísticos: tonos o formas de expresión.

- Efectores gramaticales: estructuras sintácticas sugeridas por proporciones o patrones visuales.

- Efectores compositivos: repetición, simetría, fragmentación u orden, derivados de composiciones visuales.

#### Consideraciones

Un mismo vector puede activar múltiples efectores.

Los efectores pueden ser jerarquizados, modificados o filtrados por otros mecanismos auxiliares, como la taxonomía.

Los efectores constituyen la "materia prima" de la construcción textual final, ensamblada luego en la FAE.

---
