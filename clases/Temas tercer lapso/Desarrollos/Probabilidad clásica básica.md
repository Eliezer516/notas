# Planificación
Mediante un breve recordatorio con los apuntes de la clase anterior se dará inicio a la clase, partiendo del análisis crítico y reflexivo de textos, ejemplos y definiciones extraídos de *Khan Academy*, los estudiantes aprenderán probabilidad clásica básica, abordando la definición como cociente entre casos favorables y posibles en un espacio muestral equiprobable, la identificación de eventos simples y compuestos, y la aplicación de la fórmula $P(A) = \frac{n(A)}{n(\Omega)}$, con la finalidad de que puedan resolver problemas cotidianos que impliquen azar. Para finalizar, aplicarán lo aprendido mediante la resolución de ejercicios que refuercen la comprensión del concepto, como calcular probabilidades en contextos como juegos de mesa o selección aleatoria.

**Ejercicios:**  
1. "Calcula la probabilidad de obtener un número primo al lanzar un dado justo de seis caras."  
2. "En una bolsa hay 3 canicas rojas, 2 azules y 5 verdes. ¿Cuál es la probabilidad de sacar una canica no roja?"  
3. "Si se extrae una carta de una baraja francesa estándar (52 cartas), ¿cuál es la probabilidad de que sea un rey?"  
4. "Dos monedas justas se lanzan simultáneamente. ¿Cuál es la probabilidad de obtener exactamente una cara?"
---
# Clase de Probabilidad Clásica para 1º de Bachillerato

---

## 📌 Introducción: Recordatorio y Conexión con lo Anterior

¡Bienvenidos a una nueva sesión de matemáticas! Antes de adentrarnos en el tema de hoy, vamos a activar nuestros conocimientos previos.

**Recordatorio:** En clases anteriores hemos trabajado con conceptos de **conteo** y **técnicas combinatorias**. Ahora, vamos a dar un paso adelante: no solo contaremos las posibilidades, sino que aprenderemos a medir qué tan probable es que ocurra un resultado específico.

En esta clase exploraremos el fascinante mundo de la **probabilidad clásica**, una herramienta matemática que nos permite cuantificar el azar de manera rigurosa.

---

## 1. El Concepto de Probabilidad Clásica

### 1.1 Concepto Teórico Oficial

La **probabilidad clásica** es una rama de la matemática que estudia los fenómenos aleatorios en situaciones donde todos los resultados posibles tienen la misma oportunidad de ocurrir. Se define como el **cociente** entre el número de casos favorables (los resultados que nos interesan) y el número de casos posibles (todos los resultados del experimento).

Formalmente, para un **espacio muestral equiprobable** Ω (donde todos los resultados tienen la misma probabilidad), la probabilidad de un evento A se calcula mediante la fórmula:

$$P(A) = \frac{n(A)}{n(\Omega)}$$

Donde:

- **P(A)** representa la probabilidad del evento A
- **n(A)** es el número de casos favorables (cardinal del evento A)
- **n(Ω)** es el número total de casos posibles (cardinal del espacio muestral)

Esta definición solo es aplicable cuando el espacio muestral es **equiprobable**, es decir, cuando cada resultado tiene exactamente la misma probabilidad de ocurrir.

---

### 1.2 Explicación "Nivel 5 años"

**Imagina que tienes una bolsa mágica transparente con exactamente:**

- **3 caramelos rojos** de fresa
- **2 caramelos amarillos** de limón

En total hay **5 caramelos** en la bolsa. Si metes la mano sin mirar y sacas UN caramelo:

- ¿Cuántas formas diferentes existen de que salga algo? **5 posibilidades** (porque hay 5 caramelos)
- ¿Cuántas formas hay de que salga un caramelo rojo? **3 posibilidades** (porque hay 3 rojos)

Entonces, la probabilidad de sacar caramelo rojo es **3 entre 5**, o dicho de otra forma: **3/5 de las veces** saldrá rojo si repitieras este juego muchas veces.

¡Es como dividir el pastel en partes iguales y ver cuántas partes son de tu sabor favorito!

---

### 1.3 Actividad Práctica

**Ejercicio 1:** En una clase de 30 estudiantes, se va a sortear una entrada gratis al cine mediante un sorteo aleatorio donde todos tienen la misma probabilidad de ganar.

- ¿Cuál es el espacio muestral?
- Si María, Carlos y Laura participan, ¿cuál es la probabilidad de que alguno de ellos gane?
- Si el profesor decide que solo pueden ganar las chicas (12 en total), ¿cuál es la nueva probabilidad de ganar?

**Solución guiada:**

- Ω = {todos los estudiantes} → n(Ω) = 30
- Casos favorables (ganar) = 1 → P(ganar) = 1/30 ≈ 0.033
- Para que gane María, Carlos o Laura: n(A) = 3 → P(A) = 3/30 = 1/10 = 0.1
- Solo chicas: n(A) = 12 → P(A) = 12/30 = 2/5 = 0.4

---

## 2. Espacio Muestral y Eventos

### 2.1 Concepto Teórico Oficial

El **espacio muestral** (representado por la letra griega Ω) es el conjunto de todos los resultados posibles de un experimento aleatorio. Cada resultado individual se llama **punto muestral**.

Un **evento** es un subconjunto del espacio muestral. Podemos clasificar los eventos en:

- **Evento simple (o elemental):** Consta de un único resultado posible. Ejemplo: obtener un 6 al lanzar un dado.
- **Evento compuesto:** Consta de dos o más resultados posibles. Ejemplo: obtener un número par al lanzar un dado (puede ser 2, 4 o 6).
- **Evento seguro:** Es aquel que siempre ocurre (equivale a todo el espacio muestral Ω).
- **Evento imposible:** Es aquel que nunca ocurre (se representa por el conjunto vacío ∅).

---

### 2.2 Explicación "Nivel 5 años"

**Piensa en una caja de crayons (lápices de colores):**

El **espacio muestral** es como tener TODOS los crayons de la caja juntos. Si tienes 12 colores, tu espacio muestral tiene 12 elementos.

Ahora, imagine que tu mamá te dice: "Saca un crayon de color **caliente** (rojo, naranja o amarillo)"

Eso es un **evento compuesto** porque incluye varios colores.

Si te dice: "Saca el crayon **rojo** específicamente", eso es un **evento simple** (solo un resultado posible).

¿El evento "sacar un crayon que exista"? ¡Eso siempre ocurre! Es un **evento seguro**.

¿El evento "sacar un crayon invisible"? ¡Imposible! Es un **evento imposible**.

---

### 2.3 Actividad Práctica

**Ejercicio 2:** Se lanza un dado estándar de 6 caras numeradas del 1 al 6. Define:

| Evento | Descripción | Resultados que lo forman |
|--------|-------------|--------------------------|
| A | Obtener un número primo | |
| B | Obtener un 4 | |
| C | Obtener un número mayor que 6 | |
| D | Obtener un número menor que 7 | |

**Clasifica cada evento** como simple, compuesto, seguro o imposible.

**Solución:**

- A = {2, 3, 5} → Compuesto (3 resultados)
- B = {4} → Simple (1 resultado)
- C = {} → Imposible (∅)
- D = {1, 2, 3, 4, 5, 6} → Seguro (Ω)

---

## 3. Probabilidad en Eventos Compuestos

### 3.1 Concepto Teórico Oficial

Cuando calculamos la probabilidad de **eventos compuestos**, debemos identificar correctamente todos los resultados que satisfacen la condición del evento. La probabilidad siempre será un número entre 0 y 1:

$$0 \leq P(A) \leq 1$$

Propiedades importantes:

- **P(Ω) = 1** (la probabilidad del evento seguro es 1)
- **P(∅) = 0** (la probabilidad del evento imposible es 0)

Para eventos compuestos, el cálculo sigue siendo el mismo: dividimos el número de resultados favorables entre el número total de resultados posibles.

---

### 3.2 Explicación "Nivel 5 años"

**Vamos a jugar a los dados con tu amigo:**

Tú lanzas un dado y quieres saber qué tan probable es obtener un **número par** (2, 4 o 6).

Tienes 6 posibles resultados (1, 2, 3, 4, 5, 6).
Los resultados "buenos" para ti son 3: el 2, el 4 y el 6.

Entonces: **3 divided by 6 = 1/2 = 0.5 = 50%**

¡Eso significa que la mitad de las veces (en un mundo perfecto) obtendrás un número par!

Es como decir: "De cada 6 veces que juguemos, aproximadamente 3 veces ganaré yo".

---

### 3.3 Actividad Práctica

**Ejercicio 3 (Desafío):** En un juego de mesa, se lanzan dos dados simultáneamente. Calcula la probabilidad de obtener:

a) **La suma de los dos dados es 7**
b) **La suma de los dos dados es mayor que 10**
c) **Los dos dados muestran el mismo número** (dobles)

*Ayuda: Construye una tabla con todas las combinaciones posibles (espacio muestral)*

**Solución:**

Para dos dados, hay 6 × 6 = **36 resultados posibles** en el espacio muestral.

a) Suma = 7: (1,6), (2,5), (3,4), (4,3), (5,2), (6,1) → **6 casos**
   P = 6/36 = 1/6 ≈ 0.167

b) Suma > 10 (11 o 12): (5,6), (6,5), (6,6) → **3 casos**
   P = 3/36 = 1/12 ≈ 0.083

c) Dobles: (1,1), (2,2), (3,3), (4,4), (5,5), (6,6) → **6 casos**
   P = 6/36 = 1/6 ≈ 0.167

---

## 4. Aplicaciones Cotidianas: Probabilidad en la Vida Real

### 4.1 Concepto Teórico Oficial

La probabilidad clásica tiene múltiples aplicaciones prácticas en situaciones de la vida cotidiana donde podemos identificar claramente el espacio muestral y los casos favorables. Sin embargo, es **fundamental** verificar que el espacio sea **equiprobable** antes de aplicar esta fórmula.

**Ejemplos de aplicación:**

- **Juegos de mesa y azar:** Dados, cartas, ruletas
- **Sorteos y loterías:** Selección aleatoria de ganadores
- **Decisiones cotidianas:** Cuando necesitamos cuantificar la incertidumbre

> **Importante:** La probabilidad clásica **no** se puede aplicar cuando los resultados no tienen la misma probabilidad (como en muchos fenómenos de la vida real). Para esos casos, se utilizan otros enfoques probabilísticos.

---

### 4.2 Explicación "Nivel 5 años"

**¿Alguna vez has jugado a "piedra, papel o tijera"?**

¡Vamos a analizarlo con probabilidad!

Cuando tú dices tu elección, tu amigo no sabe qué vas a elegir, así que tiene **3 opciones posibles**: piedra, papel o tijera.

Si tu amigo quiere elegir algo que te gane, tiene **1 oportunidad de 3** de elegir correctamente la opción que te vence.

Entonces: **P(ganarte) = 1/3 ≈ 33%**

¡Por eso a veces parece que tu amigo "adivina" lo que vas a hacer! En realidad, solo tiene 1 de cada 3 posibilidades de ganar automáticamente.

---

### 4.3 Actividad Práctica

**Ejercicio 4 (Aplicación cotidiana):**

**Situación A:** En un mazo de cartas español (40 cartas), se extrae una carta al azar. Calcula la probabilidad de obtener:
- Un **as**
- Una **carta de oros**
- Un **rey de espadas**

**Situación B:** En una urna hay 5 bolas rojas, 3 bolas azules y 2 bolas verdes. Se extrae una bola sin mirar. Calcula la probabilidad de obtener:
- Una **bola azul**
- **No** obtener una bola roja

**Solución Situación A:**
- Ω = 40 cartas
- Ases: 4 → P = 4/40 = 1/10 = 0.1
- Oros: 10 → P = 10/40 = 1/4 = 0.25
- Rey de espadas: 1 → P = 1/40 = 0.025

**Solución Situación B:**
- Total bolas: 5 + 3 + 2 = 10
- Azul: 3 → P = 3/10 = 0.3
- No roja (azul + verde): 3 + 2 = 5 → P = 5/10 = 0.5

---

## 📋 Resumen de la Clase

| Concepto | Fórmula | Ejemplo |
|----------|---------|---------|
| **Probabilidad clásica** | P(A) = n(A)/n(Ω) | P(sacar 6) = 1/6 |
| **Espacio muestral (Ω)** | Conjunto de todos los resultados posibles | {1, 2, 3, 4, 5, 6} |
| **Evento simple** | Un solo resultado | {6} |
| **Evento compuesto** | Varios resultados | {2, 4, 6} |
| **Evento seguro** | P = 1 | Obtener ≤ 6 en un dado |
| **Evento imposible** | P = 0 | Obtener 7 en un dado |

---

## 🎯 Tarea para Casa

1. **Investiga** un ejemplo de tu vida cotidiana donde se aplique la probabilidad clásica.
2. **Calcula** la probabilidad de que ocurra ese evento.
3. **Explica** por qué el espacio muestral es equiprobable en ese caso.

**Recordatorio:** La probabilidad nos ayuda a tomar decisiones informadas en un mundo lleno de incertidumbre. ¡Sigan practicando!