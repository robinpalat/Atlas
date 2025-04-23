---
layout: page
title: Flujo de Datos
nav_order: 7
parent: Arquitectura
has_children: true
---


# Flujo de Datos:
<br><br>

El flujo de datos en el Sistema Atlas sigue una secuencia lógica y jerárquica, diseñada para procesar y transformar información a través de diferentes etapas, desde la captura inicial hasta la salida final generada por el dispositivo léxico dinámico (DLD). El proceso se desglosa de la siguiente manera:

### 1. Vectores Primarios
Definición: Los vectores primarios representan los datos crudos adquiridos a través de sensores, que capturan las características perceptuales de los estímulos (por ejemplo, imágenes, sonidos, texturas, etc.). Estos datos son el punto de entrada al sistema.

Función: Reciben información de diversas fuentes de entrada, como sensores visuales, auditivos, táctiles, etc. En esta etapa, los vectores primarios no han sido modificados ni procesados, y su propósito es servir como la base para posteriores transformaciones.

Características: Son datos en su forma más pura, sin interpretación ni manipulación, que representan directamente las características perceptuales detectadas.

### 2. Vectores Secundarios
Definición: Los vectores secundarios son el resultado de la conversión de los vectores primarios a una forma más comprensible y operativa. En esta etapa, los datos brutos son procesados para extraer información relevante y transformados en un formato que pueda ser manipulado por los módulos del sistema.

Función: Esta transformación se lleva a cabo mediante un módulo de transducción, que toma los vectores primarios y los convierte en vectores secundarios. El objetivo es estructurar estos vectores para que puedan ser utilizados dentro del sistema, creando una representación más abstracta de los datos que permite identificar patrones y relaciones.

Características: Los vectores secundarios son procesados y optimizados para facilitar su uso en las siguientes etapas del sistema. Aquí se pueden aplicar técnicas de análisis, como la normalización de datos o la extracción de características clave.

### 3. Efectores
Definición: Los efectores son el componente final que utiliza los vectores secundarios para generar un resultado procesado. En el contexto del sistema, los efectores manipulan los vectores secundarios, transformándolos en salidas concretas, ya sea en forma de texto, imágenes, sonidos, etc.

Función: Los efectores son responsables de la interpretación final de los datos procesados, y aplican las transformaciones necesarias para generar la salida que el sistema busca producir. Esta etapa implica la activación de mecanismos como el dispositivo léxico dinámico (DLD), que organiza y genera el texto o las representaciones artísticas basadas en los vectores.

Características: Los efectores toman decisiones basadas en los vectores secundarios y producen el output final. En el caso de las salidas textuales, el DLD organiza las palabras y construye la estructura gramatical necesaria, sin entrar en el campo semántico, pero manteniendo la coherencia estética.

Resumen del Flujo de Datos:
Entrada sensorial: Vectores primarios capturan datos crudos de estímulos.

Procesamiento inicial: Los vectores primarios se convierten en vectores secundarios a través de un proceso de transducción, estructurando la información para su manipulación.

Generación de salida: Los vectores secundarios son utilizados por los efectores, que producen la salida final, como un texto procesado, visualización o acción específica, manteniendo la coherencia estética y funcional del sistema.

Este flujo de datos asegura que cada etapa del proceso esté optimizada para recibir, transformar y generar información de manera eficiente, sin ambigüedades, y con un enfoque claro en la manipulación de datos perceptuales en un entorno técnico y estructurado.

---
