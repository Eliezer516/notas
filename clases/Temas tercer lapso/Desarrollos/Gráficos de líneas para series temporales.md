# Planificación
Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de *GeoGebra.org*, los estudiantes aprenderán a construir e interpretar gráficos de líneas para series temporales, abordando la definición de series temporales, la organización de ejes de tiempo y valores, la identificación de tendencias (como subidas, bajadas o estabilidad) y aplicaciones en contextos como el análisis climático o económico, con la finalidad de que puedan interpretar y crear representaciones gráficas que reflejen datos cambiantes en el tiempo. Para finalizar, diseñarán gráficos a partir de datos reales o simulados que integren variables temporales y cuantitativas.  

**Ejercicios:**  
1. "Dado el conjunto de datos $\{(t_1, y_1), (t_2, y_2), (t_3, y_3)\} = \{(1, 5), (2, 8), (3, 3)\}$, construye el gráfico de línea en GeoGebra y describe la tendencia observada."  
2. "Interpreta la gráfica mostrada a continuación (imagina una línea que sube gradualmente de $t=0$ a $t=10$): ¿Qué podría representar este gráfico en un contexto real?"  
3. "Crea un gráfico de línea para modelar la temperatura diaria en una semana, usando $t$ (días) como eje horizontal y $T$ (grados Celsius) como vertical. Incluye al menos 5 puntos de datos."  
4. "Dado el gráfico de una serie temporal con picos irregulares, calcula el valor promedio de $y$ entre $t=2$ y $t=5$ usando la fórmula $\frac{1}{n}\sum_{i=1}^n y_i$."

---

# Clase: **Series temporales y su representación gráfica**  
*Bachillerato – 1.º año*  

---

### 1. Concepto teórico oficial  

Una **serie temporal** es una sucesión de observaciones numéricas tomadas a intervalos regulares de tiempo (diario, mensual, anual, etc.). Cada observación se representa mediante un **par ordenado** \((t_i , y_i)\) donde \(t_i\) indica el instante (eje horizontal) y \(y_i\) el valor medido (eje vertical). El objetivo de graficar una serie temporal es **visualizar la evolución** del fenómeno y detectar **tendencias** (creciente, decreciente o estable), **ciclos** y **variaciones estacionales**.  

En la práctica, se construye un **gráfico de líneas**: los puntos \((t_i , y_i)\) se unen mediante segmentos rectos, lo que permite observar de forma continua el comportamiento del dato a lo largo del tiempo.

---

### 2. Explicación “Nivel 5 años”  

Imagina que tienes una **cuerda de luces navideñas** que se enciende una a una cada día. Cada bombilla representa el **valor** que medimos (por ejemplo, la temperatura) y el día en que se enciende es el **tiempo**. Si dibujas una línea que une todas las bombillas encendidas, verás si la luz se vuelve más brillante (sube la temperatura), más tenue (baja) o si se mantiene igual (estabilidad). Así, la cuerda de luces es el **gráfico de la serie temporal** y nos ayuda a entender cómo cambian las cosas con el paso de los días.

---

### 3. Actividad práctica  

#### **Objetivo:**  
Construir e interpretar un gráfico de líneas a partir de datos reales de una serie temporal y describir la tendencia observada.

#### **Materiales:**  
- Ordenador con acceso a **GeoGebra** (o hoja cuadriculada y regla).  
- Conjunto de datos (pueden ser descargados de *https://data.worldbank.org* o usar la tabla siguiente).

| Año | Precio medio de la vivienda (USD) |
|-----|-----------------------------------|
| 2015| 210 000 |
| 2016| 215 000 |
| 2017| 220 500 |
| 2018| 225 000 |
| 2019| 230 800 |
| 2020| 240 000 |
| 2021| 250 500 |
| 2022| 260 000 |

#### **Procedimiento:**  

1. **Importar los datos** a GeoGebra (hoja de cálculo → crear tabla con columnas *Año* y *Precio*).  
2. **Crear los pares ordenados** \((t_i , y_i)\) y usar la herramienta *“Crear lista de puntos”* para generar los puntos del plano.  
3. **Unir los puntos con líneas** mediante la herramienta *“Polígono”* o *“Línea de ajuste”* para obtener el **gráfico de líneas**.  
4. **Etiquetar los ejes:**  
   - Eje horizontal (x): *Año* (tiempo).  
   - Eje vertical (y): *Precio medio de la vivienda (USD)* (valor).  
5. **Analizar la tendencia:**  
   - Calcular la **pendiente media** aproximada \(\displaystyle m \approx \frac{y_{último}-y_{primer}}{t_{último}-t_{primer}} = \frac{260\,000-210\,000}{2022-2015}= \frac{50\,000}{7}\approx 7\,143\) USD/año.  
   - Redactar, en no más de tres frases, si la serie muestra una **tendencia creciente**, **decreciente** o **estable**, y mencionar una posible causa (p. ej., mayor demanda de vivienda).  

#### **Criterios de evaluación:**  

| Criterio | Excelente (4) | Bueno (3) | Suficiente (2) | Insuficiente (1) |
|----------|---------------|-----------|----------------|------------------|
| **Construcción del gráfico** | Ejes correctos, puntos y línea perfectamente alineados | Pequeños errores de escala | Ejes etiquetados de forma confusa | No se presenta gráfico |
| **Cálculo de pendiente** | Cálculo exacto y razonamiento claro | Error menor (<5 %) | Error mayor (5‑15 %) | No calcula |
| **Interpretación de la tendencia** | Explicación clara, vinculada a contexto real | Explicación adecuada pero poco desarrollada | Mención superficial | No interpreta |

---

### 4. Cierre reflexivo  

Concluiremos la clase retomando la **analogía de la cuerda de luces**: al observar cómo la luz se vuelve más brillante o más tenue, acabamos de hacer lo mismo que hicimos con los datos de la vivienda. Cada gráfico es una “historia luminosa” que nos permite **predecir** y **planificar** decisiones en ámbitos como la economía, la climatología o la salud.  

**¡Tu misión ahora es buscar otra serie temporal (por ejemplo, la temperatura media anual de tu ciudad) y reproducir el mismo proceso!**  

---  

*Recuerda que la claridad del gráfico y la precisión del análisis son tan importantes como la creatividad al elegir los datos.*