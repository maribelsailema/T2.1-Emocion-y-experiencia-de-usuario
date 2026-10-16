# 📊 Matriz de Experiencia de Usuario (UX) — SuperOfertas Ecuador

**Proyecto:** Evaluación y Rediseño UX — SuperOfertas Ecuador  
**Asignatura:** Interacción Humano Computador (IHC)  
**Universidad:** Universidad Técnica de Ambato — FISEI  
**Grupo:** 1  


---

## 1. Introducción

La matriz de experiencia de usuario (UX) permite relacionar los momentos de interacción con las emociones, evidencias y oportunidades de mejora identificadas durante el análisis de una interfaz.

En este caso, se analiza la pantalla **"Revisa la dirección (Mapa)"** de SuperOfertas Ecuador, considerando cinco momentos de interacción distribuidos entre las etapas antes, durante y después de la tarea.

La matriz constituye una herramienta de diagnóstico para orientar el rediseño de la interfaz en Figma.

## 2. Objetivo

Construir una matriz UX que relacione cinco momentos de interacción con las emociones hipotéticas, evidencias visuales y propuestas de mejora, para identificar problemas de usabilidad y establecer criterios de rediseño centrados en el usuario.

## 3. Escala emocional

Se utilizará una escala de cinco niveles para registrar las emociones durante las pruebas.

| Valor | Nivel emocional | Interpretación |
|:---:|---|---|
| **+2** | Muy satisfecho | La interacción resulta clara y genera confianza. |
| **+1** | Satisfecho | La tarea se comprende con facilidad. |
| **0** | Neutral | No se experimentan dificultades ni satisfacción destacable. |
| **-1** | Frustrado | Existen dificultades que generan incomodidad. |
| **-2** | Muy frustrado | Existen dificultades importantes que afectan la experiencia. |

**Nota:** Los valores definitivos deberán obtenerse mediante la evaluación de al menos tres usuarios. No se asignan puntuaciones observadas antes de realizar las pruebas.

## 4. Matriz UX inicial

| N.º | Etapa | Momento de interacción | Emoción hipotética | Evidencia de la interfaz original | Propuesta de mejora |
|:---:|---|---|---|---|---|
| **1** | Antes | Llegada a la pantalla | Confusión | Predominan colores amarillo, rojo y verde, junto con mensajes promocionales y temporizador que compiten con el título principal. | Reducir la saturación visual y destacar el título y el progreso de compra. |
| **2** | Durante | Interpretación de la dirección | Incertidumbre | El mapa presenta un marcador y una dirección textual, pero la correspondencia visual entre ambos no resulta evidente. | Incorporar una tarjeta de dirección con información organizada y un marcador claramente asociado a la ubicación. |
| **3** | Durante | Exploración de controles | Frustración leve | Los controles del mapa son pequeños y presentan poca diferenciación visual. | Mejorar el tamaño, contraste y reconocimiento de los controles de interacción. |
| **4** | Durante | Selección de la acción | Confusión | El botón "Omitir" destaca visualmente, mientras que "Guardar dirección" presenta apariencia deshabilitada. | Priorizar la acción principal, diferenciar acciones secundarias y explicar los estados de los botones. |
| **5** | Después | Resultado de la decisión | Incertidumbre | La captura no muestra el estado posterior ni una confirmación visible de la acción seleccionada. | Diseñar un estado de confirmación que comunique si la dirección fue guardada o si el usuario decidió omitirla. |

## 5. Análisis de las oportunidades de mejora

### Mejora 1. Organización y jerarquía visual

**Problema:** Los elementos promocionales y los colores intensos compiten con la información necesaria para completar la tarea.

**Propuesta:** Reorganizar la pantalla para destacar el título, el mapa y la dirección, manteniendo los elementos promocionales en una posición secundaria.

**Principios relacionados:** Jerarquía visual, proximidad y región común de Gestalt.

### Mejora 2. Claridad de la ubicación

**Problema:** La relación entre la dirección escrita y la ubicación del mapa no resulta suficientemente evidente.

**Propuesta:** Presentar la dirección en una tarjeta claramente identificada y asociarla visualmente con el marcador del mapa.

**Principios relacionados:** Correspondencia entre sistema y mundo real, consistencia y reconocimiento antes que recuerdo.

### Mejora 3. Reconocimiento de controles

**Problema:** Los controles del mapa son pequeños y no destacan suficientemente.

**Propuesta:** Mejorar su tamaño, contraste, separación y etiquetas accesibles.

**Principios relacionados:** Accesibilidad, affordance y prevención de errores.

### Mejora 4. Claridad de las acciones

**Problema:** El botón "Omitir" presenta mayor prominencia visual que la acción de guardar dirección.

**Propuesta:** Establecer una jerarquía clara entre las acciones principales y secundarias, explicando cuándo se puede guardar una dirección y qué implica omitir la verificación.

**Principios relacionados:** Control y libertad del usuario, prevención de errores y consistencia.

### Mejora 5. Retroalimentación del sistema

**Problema:** La captura original no permite comprobar si el sistema informa al usuario sobre el resultado de su decisión.

**Propuesta:** Diseñar mensajes de confirmación o estados posteriores que indiquen claramente el resultado de guardar u omitir la dirección.

**Principios relacionados:** Visibilidad del estado del sistema y retroalimentación.

## 6. Priorización inicial de mejoras

| Prioridad | Mejora | Justificación |
|---|---|---|
| **Alta** | Claridad de las acciones | Puede afectar directamente la decisión de guardar u omitir la dirección. |
| **Alta** | Claridad de la ubicación | Es fundamental para verificar correctamente el lugar de entrega. |
| **Alta** | Retroalimentación del sistema | Permite comprender si la acción fue completada. |
| **Media** | Organización y jerarquía visual | Facilita la comprensión y reduce distracciones. |
| **Media** | Reconocimiento de controles | Mejora la interacción y accesibilidad del mapa. |

Esta priorización es preliminar y podrá modificarse a partir de los resultados de las pruebas.

## 7. Relación con la evaluación de usuarios

Para completar la matriz con evidencia empírica, se utilizarán los resultados de la Issue #2.

Se deberán incorporar:

- Las emociones registradas por los tres participantes.
- Las puntuaciones de cada momento de interacción.
- Las dificultades realmente observadas.
- Los comentarios relevantes de los usuarios.
- Las evidencias disponibles de las pruebas.

La matriz inicial servirá como referencia para determinar cuáles problemas fueron confirmados y cuáles requieren ajustes.

## 8. Conclusión

La matriz UX inicial identifica cinco oportunidades de mejora relacionadas con la organización visual, la interpretación de la ubicación, los controles del mapa, las acciones principales y la retroalimentación del sistema.

Las propuestas permitirán orientar el rediseño en Figma y establecer criterios para evaluar posteriormente si los cambios realizados mejoran la experiencia de los usuarios.

La validación definitiva dependerá de las pruebas iniciales y de la comparación posterior al rediseño.