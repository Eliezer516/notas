---
title: funciones
date: 29-09-2025
draft: false
---

### **Clase 1: Introducción a las funciones**  
**Objetivo:** Comprender qué es una función y cómo se representa.

- **Definición de función**:  
  Una función $f$ es una regla que asigna a **cada elemento** del conjunto de partida (dominio) **exactamente un elemento** del conjunto de llegada (codominio).
  
- **Notación**:  
  $f: A \rightarrow B$, donde $A$ es el dominio y $B$ el codominio.  
  Se escribe $y = f(x)$, donde $x$ es la variable independiente e $y$ la dependiente.

- **Formas de representar funciones**:  
  - Tablas de valores  
  - Gráficas  
  - Expresiones algebraicas  
  - Diagramas de flechas  

- **Prueba de la recta vertical**:  
  Si una recta vertical corta la gráfica en más de un punto, **no es una función**.

---

### **Clase 2: Dominio, rango y tipos de funciones**  
**Objetivo:** Identificar dominio, rango y clasificar funciones según su comportamiento.

- **Dominio**: Conjunto de todos los valores posibles de $x$ para los que $f(x)$ está definida.  
- **Rango (o imagen)**: Conjunto de todos los valores que toma $f(x)$.

- **Tipos comunes de funciones**:
  - **Función constante**: $f(x) = c$
  - **Función lineal**: $f(x) = mx + b$
  - **Función cuadrática**: $f(x) = ax^2 + bx + c$
  - **Función polinómica**: suma de potencias de $x$
  - **Función racional**: cociente de polinomios
  - **Función valor absoluto**: $f(x) = |x|$
  - **Función raíz cuadrada**: $f(x) = \sqrt{x}$

- **Criterios para hallar dominio**:  
  - Denominadores $\neq 0$  
  - Expresiones bajo raíces pares $\geq 0$  
  - Logaritmos: argumento $> 0$

---

### **Clase 3: Propiedades y transformaciones de funciones**  
**Objetivo:** Analizar características clave y cómo se modifican las gráficas.

- **Crecimiento y decrecimiento**:  
  - Creciente: si $x_1 < x_2 \Rightarrow f(x_1) < f(x_2)$  
  - Decreciente: si $x_1 < x_2 \Rightarrow f(x_1) > f(x_2)$

- **Máximos y mínimos**:  
  - Absolutos y relativos (locales)

- **Simetría**:  
  - **Par**: $f(-x) = f(x)$ → simétrica respecto al eje $Y$  
  - **Impar**: $f(-x) = -f(x)$ → simétrica respecto al origen

- **Transformaciones gráficas**:  
  - Traslaciones verticales/horizontales: $f(x) + k$, $f(x - h)$  
  - Reflexiones: $-f(x)$, $f(-x)$  
  - Estiramientos/compresiones: $a \cdot f(x)$, $f(bx)$

---

### **Clase 4: Operaciones con funciones y funciones inversas**  
**Objetivo:** Combinar funciones y entender la relación inversa.

- **Operaciones algebraicas**:  
  Dadas $f$ y $g$:  
  - Suma: $(f + g)(x) = f(x) + g(x)$  
  - Resta, producto, cociente (con $g(x) \neq 0$)

- **Composición de funciones**:  
  $(f \circ g)(x) = f(g(x))$  
  Importante: **no es conmutativa** en general.

- **Función inversa**:  
  - Solo existe si la función es **biyectiva** (inyectiva y sobreyectiva).  
  - Se denota $f^{-1}$ y cumple:  
    $f(f^{-1}(x)) = x$ y $f^{-1}(f(x)) = x$  
  - Gráficamente, $f$ y $f^{-1}$ son simétricas respecto a la recta $y = x$.

- **Cálculo de la inversa**:  
  1. Escribir $y = f(x)$  
  2. Despejar $x$ en términos de $y$  
  3. Intercambiar $x$ e $y$
