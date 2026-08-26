# Tablero de priorización

## Hipótesis 1

| Campo | Valor |
|---|---|
| Causa | Los residentes tienen dificultades para identificar cómo deben clasificar y aprovechar los diferentes tipos de residuos que generan en sus hogares. |
| Fase DT origen (E/D/I) | Arbol de problemas: No se encontro información suficiente en cuanto a como clasificar los residuos en el conjunto forte puerta del sol  |
| Insight de empatía | Me preocupa que los residuos generen malos olores. |
| Supuesto central | Si implementamos una estrategia de información y orientación sobre la clasificación y aprovechamiento de los residuos, entonces los residentes identificarán correctamente cómo clasificar y aprovechar los diferentes tipos de residuos que generan en sus hogares. |
| Pregunta analítica | ¿Cómo varía la capacidad de los residentes para identificar y clasificar los diferentes tipos de residuos según su nivel de exposición a la estrategia de información y orientación sobre el manejo de residuos? |
| Variables (nombres exactos) | 1. Porcentaje de residentes que identifican correctamente cómo clasificar y aprovechar los diferentes tipos de residuos<br>2.nivel_exposicion_estrategia<br>3.capacidad_clasificacion_residuos<br>4.resident_id <br>5.campana_informacion_expuesto<br>6.identificacion_correcta_residuos<br>7.fecha_medicion<br>8.conocimiento_aprovechamiento_residuos<br>9.participacion_actividad_informativa |
| Tipo (Outcome / Explic / Control / Segmento) | 1.Indicador KPI<br>2.Variable Explicativa (X) 3.Variable Outcome (Y): <br>4.Segmento <br>5.Explicativa (X)<br>6.Outcome (Y)<br>7.Segmento<br>8.Outcome (Y)<br>9.Explicativa (X) |
| Cálculo / Transformación |  |
| Métrica (nombre + fórmula) | **Porcentaje de residentes que identifican correctamente cómo clasificar y aprovechar los diferentes tipos de residuos<br><br><br><br>(Número de residentes que identifican correctamente los residuos ÷ Número total de residentes que participaron en la campaña) × 100** |
| Periodo / Segmento | Mensual: Una vez al mes. |
| Patrón esperado (si cierta) | ≥ 63 % |
| Condición refutación | **< 60 %** |
| Valor esperado para usuario/ciudadano | Los residentes sentirán mayor seguridad y satisfacción al manejar correctamente sus residuos, y de forma tangible lograrán clasificar y aprovechar adecuadamente los residuos que generan en sus hogares, contribuyendo a un entorno más limpio y organizado. |
| Riesgo si falsa | Los residentes continuarán presentando dificultades para clasificar y aprovechar correctamente los residuos, sin generar un cambio real y sostenible en su manejo dentro del conjunto. |
| Acción si confirma | Replicar la estrategia de información a todos los residentes del conjunto. |
| Acción si refuta | Realizar una encuesta corta para identificar qué residuos generan mayor confusión. |
| Experimento analítico mínimo (query + visual 1 línea) |  |
| Estado (V/A/R) |  |

## Hipótesis 2

| Campo | Valor |
|---|---|
| Causa | Los residuos se depositan en espacios que dificultan mantenerlos separados y organizados hasta el momento de su recolección. |
| Fase DT origen (E/D/I) | Empatizar: Se hablo con natalia Aguirre y comunico que al desechar sus residuos evidencio que los residentes no realizaban una adecuada separacion de estos residuos al ver una mezcla de residuos y desorden en el lugar de almacenamiento  |
| Insight de empatía | Me gustaría que existiera mayor compromiso de todos los residentes. |
| Supuesto central | Si adecuamos los espacios destinados a la disposición de residuos para facilitar su separación y organización, entonces los residuos se mantendrán separados y organizados hasta el momento de su recolección. |
| Pregunta analítica | ¿Cómo varía el nivel de separación y organización de los residuos según las condiciones de los espacios destinados a su disposición? |
| Variables (nombres exactos) | 1 Porcentaje de residuos que permanecen correctamente separados y organizados en los puntos de disposición hasta el momento de su recolección.<br>2.condiciones_punto_disposicion<br>3.nivel_separacion_organizacion_residuos<br>4.id_punto_disposicion<br>5.tipo_residuo<br>6.adecuacion_punto_disposicion<br>7.separacion_residuos<br>8.organizacion_residuos<br>9.estado_recoleccion<br>10.momento_medicion |
| Tipo (Outcome / Explic / Control / Segmento) | 1. Indicador KPI<br>2.Variable Explicativa (X) <br>3.Variable Outcome (Y):<br>4.Segmento<br>5.Explicativa (X)<br>6.Explicativa (X)<br>7.Outcome (Y)<br>8.Outcome (Y)<br>9.Outcome (Y)<br>10.Segmento |
| Cálculo / Transformación |  |
| Métrica (nombre + fórmula) | **Porcentaje de residuos que permanecen correctamente separados y organizados en los puntos de disposición hasta el momento de su recolección<br><br>(Número de residuos que permanecen correctamente separados y organizados ÷ Número total de residuos observados) × 100** |
| Periodo / Segmento | Semanal: Una vez a la semana. |
| Patrón esperado (si cierta) | ≥ 50 % |
| Condición refutación | **< 49%** |
| Valor esperado para usuario/ciudadano | El residente tendrá mayor facilidad para separar los residuos y mayor satisfacción al contar con espacios limpios, organizados y funcionales. |
| Riesgo si falsa | Los residentes podrían continuar enfrentando dificultades para separar correctamente los residuos, generando desorden y mezcla de residuos en los puntos de disposición |
| Acción si confirma | Implementar y mantener la adecuación de los puntos de disposición en el conjunto. |
| Acción si refuta | Revisar otras causas que estén generando la mezcla y desorganización de los residuos. |
| Experimento analítico mínimo (query + visual 1 línea) |  |
| Estado (V/A/R) |  |

## Hipótesis 3

| Campo | Valor |
|---|---|
| Causa | Algunos residentes no mantienen de manera constante las prácticas establecidas en la normativa  para la correcta disposición de los residuos. |
| Fase DT origen (E/D/I) | Empatizar: Se evidencia cuando se encuentra el desorden en el lugar de almacenamiento y la mezcla de estos residuos |
| Insight de empatía | Quiero vivir en un ambiente limpio y agradable. |
| Supuesto central | Si implementamos mecanismos de seguimiento y recordatorios sobre las prácticas establecidas en la normativa para la disposición de residuos, entonces los residentes mantendrán de manera constante dichas prácticas. |
| Pregunta analítica | ¿Cómo varía la frecuencia con la que los residentes cumplen las prácticas establecidas en la normativa según su nivel de exposición a los mecanismos de seguimiento y recordatorios? |
| Variables (nombres exactos) | 1.Porcentaje de cumplimiento de las prácticas de disposición de residuos<br>2.nivel_exposicion_mecanismos_seguimiento_recordatoriosde residuos. <br>3.frecuencia_cumplimiento_practicas_disposicion_residuos<br>4.id_residente<br>5.nivel_exposicion_mecanismos_seguimiento_recordatorios<br>6.seguimiento_practicas<br>7.recordatorios_practicas<br>8.frecuencia_cumplimiento_practicas_disposicion_residuos<br>9.fecha_medicion<br>10.momento_medicion |
| Tipo (Outcome / Explic / Control / Segmento) | 1.Indicador KPI<br>2.Variable Explicativa (X) <br>3.Variable Outcome (Y):<br>4.Segmento<br>5.Explicativa<br>6.Explicativa<br>7.Explicativa<br>8.Outcome<br>9.Segmento<br>10.Segmento |
| Cálculo / Transformación |  |
| Métrica (nombre + fórmula) | **Porcentaje de cumplimiento de las prácticas de disposición de residuos<br><br>(Número de residentes que cumplen correctamente las prácticas / Número total de residentes evaluados) × 100** |
| Periodo / Segmento | Mensual: Una vez al mes. |
| Patrón esperado (si cierta) | ≥ 70% |
| Condición refutación | **< 65%** |
| Valor esperado para usuario/ciudadano | Los residentes mantendrán de manera constante las prácticas correctas de disposición de residuos. |
| Riesgo si falsa | Los residentes podrían continuar incumpliendo las prácticas de disposición, aun después de recibir seguimiento y recordatorios. |
| Acción si confirma | Mantener y fortalecer los mecanismos de seguimiento y recordatorios. |
| Acción si refuta | Identificar otras causas del incumplimiento y ajustar la estrategia de intervención. |
| Experimento analítico mínimo (query + visual 1 línea) |  |
| Estado (V/A/R) |  |

# Ficha de Indicador

## Hipótesis 1

| Campo | Valor |
|---|---|
| Supuesto central | Si implementamos una estrategia de información y orientación sobre la clasificación y aprovechamiento de los residuos, entonces los residentes identificarán correctamente cómo clasificar y aprovechar los diferentes tipos de residuos que generan en sus hogares. |  |
| ¿QUÉ HAGO? (Acción) | Implementar una campaña de información sobre la clasificación y aprovechamiento de los residuos. |
| ¿CÓMO LO HAGO? (Método) | Difundir material educativo mediante carteles, piezas digitales y mensajes informativos en las zonas comunes y canales de comunicación del conjunto. |
| ¿PARA QUÉ LO HAGO? (Propósito) | Lograr que los residentes reconozcan cómo clasificar y aprovechar los diferentes tipos de residuos que generan en sus hogares. |
| Aspecto específico a Medir | Porcentaje de residentes que identifican correctamente cómo clasificar y aprovechar los diferentes tipos de residuos después de recibir la campaña de información. |
| Público objetivo (Para quién): | Residentes del conjunto Forte Puerta del Sol |
| Dimensión (Marca una) | Eficacia (¿Logra el resultado?) |
| Nombre del indicador | **Porcentaje de residentes que identifican correctamente cómo clasificar y aprovechar los diferentes tipos de residuos** |
| Numerador (Variable Y) | Número de residentes que identifican correctamente cómo clasificar y aprovechar los diferentes tipos de residuos después de recibir la campaña de información. |
| Denominador (Población) | Número total de residentes que participaron o recibieron la campaña de información. |
| Fórmula (Matemática) | `(Número de residentes que identifican correctamente los residuos ÷ Número total de residentes que participaron en la campaña) × 100` |
| Prueba de estrés | La prueba de estrés del indicador consiste en verificar que el porcentaje obtenido represente realmente el nivel de identificación de los residentes y no se vea afectado por una participación insuficiente o por respuestas que no reflejen sus conocimientos. Para ello, se debe comprobar que el número de residentes evaluados sea representativo de quienes recibieron la campaña, que cada residente sea contabilizado una sola vez y que la identificación correcta se determine mediante preguntas o ejercicios relacionados con la clasificación y aprovechamiento de residuos. De esta manera, el indicador permitirá establecer si la campaña está asociada con el resultado esperado y evitará interpretar como un logro un porcentaje elevado obtenido a partir de una cantidad muy pequeña de participantes. |
| Tipo (Marca una) | Porcentaje (%) |
| Frecuencia de medición | Mensual: Una vez al mes. |
| Fuente de datos (Verificación) | Resultado de cuestionario(nombre del cuestionario) |
| Línea base (Patrón actual) | 0.54 |
| Patrón esperado (Meta) | ≥ 63 % |
| Condición de refutación (Fallo). Es el número que te dice que tu idea no funcionó. | **< 60 %** |

## Hipótesis 2

| Campo | Valor |
|---|---|
| Supuesto central | Si adecuamos los espacios destinados a la disposición de residuos para facilitar su separación y organización, entonces los residuos se mantendrán separados y organizados hasta el momento de su recolección. |
| ¿QUÉ HAGO? (Acción) | Organizar los puntos de disposición de residuos según el tipo de residuo. |
| ¿CÓMO LO HAGO? (Método) | Distribuir los recipientes en espacios definidos, separados entre sí y con señalización visible para cada categoría de residuo. |
| ¿PARA QUÉ LO HAGO? (Propósito) | Evitar la mezcla de residuos y mantenerlos organizados hasta su recolección. |
| Aspecto específico a Medir | Porcentaje de residuos que permanecen correctamente separados y organizados en los puntos de disposición hasta el momento de su recolección. |
| Público objetivo (Para quién): | Residentes del conjunto Forte Puerta del Sol |
| Dimensión (Marca una) | Eficacia (¿Logra el resultado?) |
| Nombre del indicador | **Porcentaje de residuos que permanecen correctamente separados y organizados en los puntos de disposición hasta el momento de su recolección** |
| Numerador (Variable Y) | Número de residuos que permanecen correctamente separados y organizados hasta el momento de su recolección |
| Denominador (Población) | Número total de residuos observados en los puntos de disposición durante el periodo de medición |
| Fórmula (Matemática) | `(Número de residuos que permanecen correctamente separados y organizados ÷ Número total de residuos observados) × 100` |
| Prueba de estrés | Para este indicador, debemos comprobar que se observen suficientes residuos y que las observaciones se realicen en diferentes momentos, no solamente cuando los puntos de disposición están recién organizados o tienen pocos residuos. También debemos verificar que cada residuo observado se registre una sola vez y que exista un criterio claro para determinar cuándo un residuo está correctamente separado y organizado. Así evitamos, por ejemplo, obtener un 100 % simplemente porque hicimos la medición justo después de organizar los puntos de disposición. |
| Tipo (Marca una) | Porcentaje (%) |
| Frecuencia de medición | Semanal: Una vez a la semana. |
| Fuente de datos (Verificación) | Cuestionario |
| Línea base (Patrón actual) | 0.437 |
| Patrón esperado (Meta) | ≥ 50 % |
| Condición de refutación (Fallo). Es el número que te dice que tu idea no funcionó. | **< 49%** |

## Hipótesis 3

| Campo | Valor |
|---|---|
| Supuesto central |Si implementamos mecanismos de seguimiento y recordatorios sobre las prácticas establecidas en la normativa para la disposición de residuos, entonces los residentes mantendrán de manera constante dichas prácticas.|
| ¿QUÉ HAGO? (Acción) | Realizar seguimiento periódico a las prácticas de disposición de residuos de los residentes. |
| ¿CÓMO LO HAGO? (Método) | Mediante observaciones programadas y registro de los incumplimientos identificados. |
| ¿PARA QUÉ LO HAGO? (Propósito) | Para identificar fallas recurrentes y promover el cumplimiento constante de la normativa. |
| Aspecto específico a Medir | Cumplimiento de las prácticas de disposición de residuos |
| Público objetivo (Para quién): | Residentes del conjunto Forte Puerta del Sol |
| Dimensión (Marca una) | Eficacia (¿Logra el resultado?) |
| Nombre del indicador | **Porcentaje de cumplimiento de las prácticas de disposición de residuos** |
| Numerador (Variable Y) | Número de residentes que cumplen correctamente las prácticas de disposición de residuos |
| Denominador (Población) | Número total de residentes evaluados |
| Fórmula (Matemática) | `(Número de residentes que cumplen correctamente las prácticas / Número total de residentes evaluados) × 100` |
| Prueba de estrés | La prueba consistiría en verificar el comportamiento del indicador bajo diferentes escenarios de cumplimiento de los residentes, especialmente en los extremos de 0 % y 100 %, comprobando que el resultado siempre se encuentre entre estos valores, que aumente cuando aumenta el número de residentes que cumplen las prácticas y que disminuya cuando aumenta el número de residentes que incumplen. De esta manera, se valida que el indicador represente correctamente el nivel de cumplimiento de las prácticas de disposición de residuos y permita identificar si es necesario implementar acciones correctivas. |
| Tipo (Marca una) | Porcentaje (%) |
| Frecuencia de medición | Mensual: Una vez al mes. |
| Fuente de datos (Verificación) | Cuestionario  |
| Línea base (Patrón actual) | 0.62 |
| Patrón esperado (Meta) | ≥ 70% |
| Condición de refutación (Fallo). Es el número que te dice que tu idea no funcionó. | **< 65%** |
