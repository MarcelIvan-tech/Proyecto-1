>      # Proyecto: [Proyecto: Sistema de Control de Calidad para Aplicación de Movilidad Urbana]

## **Resumen Ejecutivo**

Diseñé y ejecuté un análisis comprehensivo de calidad para dos componentes críticos de una aplicación de movilidad: el sistema de registro de licencias de conducir y el algoritmo de cálculo de tiempo y costo de viajes. El proyecto implementó técnicas avanzadas de diseño de pruebas que permitieron identificar requisitos ambiguos y validar la lógica de negocio fundamental.


### **Metodologías de Testing Aplicadas**

- **Análisis de Requerimientos**: Identificación de especificaciones funcionales y "zonas grises"
- **Pruebas de Caja Negra**: Validación de funcionalidad sin conocimiento interno
- **Técnicas de Diseño de Pruebas**: Clases de equivalencia, valores límite y diagramas de flujo
- **Validación de Lógica de Negocio**: Verificación de algoritmos de cálculo complejos

## **Componentes Principales del Análisis**

### **1. Mapa Mental para Función "Agregar Licencia de Conducir"**

- **Análisis de Interfaz**: Diseño visual y elementos UI de la ventana emergente
- **Análisis de Funcionalidad**: Comportamiento del sistema con entradas válidas e inválidas
- **Identificación de "Zonas Grises"**: Requerimientos incompletos o ambiguos documentados
- **Estructura Jerárquica**: Organización lógica de componentes y subcomponentes

### **2. Clases de Equivalencia para Campos "Nombre" y "Apellido"**

- **Validación de Longitud**: Rango 2-14 caracteres con casos límite
- **Validación de Caracteres**: Letras latinas, espacios y guiones vs. caracteres no permitidos
- **Casos Negativos**: Campos vacíos, longitud excesiva, caracteres inválidos
- **Valores Límite**: "Jo" (2 caracteres), "AlexanderJohns" (14 caracteres)

### **3. Diagrama de Flujo para Selección de Velocidad**

- **Lógica Basada en Horarios**: 5 intervalos temporales con velocidades específicas
- **Toma de Decisiones**: Flujo condicional según hora de salida
- **Velocidades Definidas**: 45 km/h (nocturno), 30 km/h (pico matutino), 40 km/h (diurno), 25 km/h (pico vespertino)
- **Algoritmo Optimizado**: Selección automática sin intervención del usuario

### **4. Casos de Prueba para Cálculo de Duración y Precio**

- **6 casos de prueba** para diferentes intervalos horarios
- **Fórmulas Validadas**: T = S/V y Precio = T × precio por minuto
- **Cobertura Completa**: Todos los rangos horarios y caso de distancia cero
- **Resultados Esperados**: Cálculos precisos de duración (1.9-3.4 minutos) y precio ($0.19-$0.34)

### **Resultados del Análisis**

- **Identificación de 5 "zonas grises"** en requerimientos de licencias
- **Definición de 16 valores de prueba** para validación de campos
- **Coverage del 100%** de escenarios de velocidad por horario
- **Documentación exhaustiva** de comportamientos esperados del sistema

### **Hallazgos Técnicos**

- **Lógica de Velocidad**: Sistema adaptativo basado en patrones de tráfico reales
- **Validación de Entrada**: Mecanismos robustos para nombres y apellidos
- **Cálculos Precisos**: Algoritmos que consideran múltiples variables contextuales
- **Experiencia de Usuario**: Flujos intuitivos para registro de licencias

## **Herramientas y Metodologías**

### **Stack Tecnológico**

- **Herramientas de Diagramación**: [draw.io](https://draw.io/) para mapas mentales y diagramas de flujo
- **Documentación**: Google Sheets para clases de equivalencia y casos de prueba
- **Metodologías**: Técnicas ISTQB para diseño de pruebas

### **Habilidades Demostradas**

- Pensamiento sistémico para análisis de requerimientos
- Capacidad para identificar ambigüedades en especificaciones
- Diseño de casos de prueba basados en técnicas formales
- Visualización de procesos complejos mediante diagramas
- Validación de algoritmos matemáticos y lógica de negocio
- Documentación técnica clara y estructurada

## **Valor Aportado**

Este proyecto se establecieron los fundamentos para la validación de componentes críticos de la aplicación, asegurando que el registro de licencias de conducir fuera robusto y seguro, mientras que los cálculos de viajes fueran precisos y confiables. El análisis profundo de requerimientos y la aplicación de técnicas formales de testing permitieron identificar áreas de mejora antes de la implementación, reduciendo riesgos y costos asociados con correcciones posteriores.

