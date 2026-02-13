---
copilot-command-context-menu-enabled: true
copilot-command-slash-enabled: true
copilot-command-context-menu-order: 0
copilot-command-model-key: ""
copilot-command-last-used: 1770916160627
---
Dado un concepto académico de nivel de bachillerato como INPUT, genera un único objetivo de aprendizaje seguido —**solo si corresponde a una materia STEM** (matemáticas, física, química, biología u otras ciencias)— de una sección de ejercicios, respetando **exactamente esta estructura**:

> **Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de [fuente confiable], los estudiantes aprenderán [concepto], abordando [elementos clave del tema] con la finalidad de que [propósito o competencia específica]. Para finalizar, [actividad de refuerzo contextualizada, sin repetir textualmente la del INPUT].**  
>  
> **Ejercicios:**  
> [lista numerada de ejercicios en formato LaTeX].

**Requisitos generales:**

- Usa **siempre y textualmente** la frase inicial: *“Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de…”*  
- La **fuente** debe ser una página educativa realista y confiable según el área (ej.: *Khan Academy*, *Purplemath*, *GeoGebra.org*, *Biologia.net*, *Quimica.net*, *FisicaModernaySimple.org*, *HistoriaNacional.edu*, *Literatura.org*, etc.).  
- **[Concepto]**: nombre claro del tema.  
- **[Elementos clave del tema]**: 2–4 aspectos esenciales (definiciones, principios, componentes, etc.), expresados de forma fluida.  
- **[Propósito o competencia específica]**: debe comenzar con verbos como *“comprendan”*, *“puedan”*, *“reconozcan”*, *“interpreten”*, *“apliquen”*, etc.  
- **[Actividad de refuerzo]**: comienza con *“Para finalizar,”* y **no repitas textualmente** la actividad mencionada en el INPUT. En su lugar, **reformula con contexto pedagógico** (ej.: si el INPUT dice *“resolviendo cinco ejercicios sencillos”*, escribe *“aplicarán lo aprendido mediante la resolución de ejercicios que refuercen la comprensión del concepto”*).

**Regla para ejercicios (áreas STEM):**

- **Si el INPUT pertenece a matemáticas, física, química, biología u otra ciencia**, **debes incluir la sección “Ejercicios:”**, **incluso si no se menciona explícitamente una actividad de refuerzo**.  
  - Si el INPUT **especifica una actividad con número y tipo** (ej.: *“cinco ejercicios de gráficas”*), genera **ese número exacto** de ejercicios alineados con la descripción.  
  - Si el INPUT **no especifica cantidad**, elige un número razonable (**3 a 5 ejercicios**) según la complejidad del tema.  
  - Los ejercicios deben ser **variados, representativos y alineados con el propósito del aprendizaje**.  
  - Usa **notación LaTeX en línea con `$...$`** para todas las expresiones matemáticas, químicas o simbólicas.  
  - Cada ejercicio debe ir **entre comillas** y en una **lista numerada**.

- **Si el INPUT pertenece a áreas no STEM** (historia, literatura, filosofía, etc.), **omite por completo la sección “Ejercicios:”**, incluso si se mencionan actividades genéricas.

**Restricciones:**

- El resultado debe contener **un solo párrafo descriptivo**, seguido **solo en materias STEM** por la sección **“Ejercicios:”**.  
- **No incluyas indicadores de evaluación, viñetas, ni frases como “Se emplearán una escala…”**  
- Usa lenguaje claro, educativo y orientado al estudiante.  
- Varía el vocabulario (verbos, elementos conceptuales) para evitar repeticiones innecesarias.

---

**Ejemplos (n-shot):**

1. **INPUT:**  
   Función afín, resolverán cinco ejercicios sencillos  
   **OUTPUT:**  
   Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de *GeoGebra.org*, los estudiantes aprenderán qué es la función afín, abordando su forma algebraica $f(x) = mx + b$, el significado de la pendiente y la ordenada al origen, y su representación gráfica, con la finalidad de que puedan modelar relaciones lineales en contextos reales. Para finalizar, aplicarán lo aprendido mediante la resolución de ejercicios que refuercen la evaluación y análisis de funciones afines.  

   **Ejercicios:**  
   1. "Dada la función afín $f(x) = -3x + 7$, calcula los valores de $f(0)$ y $f(1)$."  
   2. "Dada la función afín $g(x) = 2x - 5$, calcula los valores de $g(3)$ y $g(-1)$."  
   3. "Dada la función afín $h(x) = -x + 4$, calcula los valores de $h(5)$ y $h(-5)$."  
   4. "Determina la pendiente y la ordenada al origen de la función $p(x) = \frac{1}{2}x - 3$."  
   5. "Escribe la expresión de una función afín cuya gráfica pasa por $(0, 2)$ y tiene pendiente $-4$."

2. **INPUT:**  
   Balanceo de ecuaciones químicas mediante seis ejercicios por tanteo  
   **OUTPUT:**  
   Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de *Quimica.net*, los estudiantes aprenderán el balanceo de ecuaciones químicas, abordando el principio de conservación de la masa, la identificación de reactivos y productos, y el método por tanteo, con la finalidad de que puedan representar correctamente transformaciones químicas. Para finalizar, practicarán el balanceo de ecuaciones mediante una serie de ejercicios progresivos que refuercen el dominio del método por tanteo.  

   **Ejercicios:**  
   1. "Balancea la ecuación: $ \text{H}_2 + \text{O}_2 \rightarrow \text{H}_2\text{O} $."  
   2. "Balancea la ecuación: $ \text{Fe} + \text{O}_2 \rightarrow \text{Fe}_2\text{O}_3 $."  
   3. "Balancea la ecuación: $ \text{CH}_4 + \text{O}_2 \rightarrow \text{CO}_2 + \text{H}_2\text{O} $."  
   4. "Balancea la ecuación: $ \text{Al} + \text{Cl}_2 \rightarrow \text{AlCl}_3 $."  
   5. "Balancea la ecuación: $ \text{Na} + \text{H}_2\text{O} \rightarrow \text{NaOH} + \text{H}_2 $."  
   6. "Balancea la ecuación: $ \text{C}_3\text{H}_8 + \text{O}_2 \rightarrow \text{CO}_2 + \text{H}_2\text{O} $."

3. **INPUT:**  
   Comunicación no verbal  
   **OUTPUT:**  
   Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de *PsicologiaYmente.com*, los estudiantes aprenderán qué es la comunicación no verbal, abordando sus componentes principales, diferencias con la comunicación verbal y manifestaciones en contextos sociales, con la finalidad de que interpreten con precisión señales gestuales, posturales y faciales en interacciones cotidianas. Para finalizar, analizarán escenas breves de interacciones reales para identificar y reflexionar sobre los elementos no verbales presentes.