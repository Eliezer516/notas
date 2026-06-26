# 🏰 BuJo Dungeon
**Dungeon-crawler táctico para tu libreta de puntos**

Necesitas: un d6, lápiz, borrador y cuaderno cuadriculado/punteado.

---

## 👤 FICHA DEL HÉROE

```
VIDAS:    [██████████] 10/10        FUERZA: 3  (Daño = 1 + Fuerza - 3)
ESCUDO:   [3/3] usos                 MOCHILA: [____] [____] [____] [____]
```

**Kits de Inicio** (elige uno, inmutable durante la partida):

| Kit | Contenido | Estilo |
|:---:|:---|:---|
| 🛡️ **Clásico** | Poción · Escudo · Comodín · Vacío | Equilibrado |
| ⚔️ **Guerrero** | Escudo · Escudo · Poción · Vacío | Tanque (sin escape) |
| 🦶 **Explorador** | Comodín · Comodín · Poción · Vacío | Evasivo (sin reparar escudo) |
| 🧪 **Alquimista** | Poción · Poción · Escudo · Vacío | Supervivencia (sin escape) |

> **Items:**  
> **Poción** → Cura 3 HP (acción libre, no consume turno).  
> **Escudo** → Repara tus usos de escudo a 3/3.  
> **Comodín** → Escapa de una habitación sin combatir.  
> **Vacío** → Se rellena con el primer cofre que encuentres.

---

## 🎮 MODOS DE JUEGO

| Modo | Preparación | Final | Notas |
|:---|:---|:---|:---|
| **⏱️ Express** | Ninguna | Habitación 10: Jefe (5V) | 10 minutos. Ideal para primeras partidas. |
| **🗺️ Delimitado** | Dibuja un rectángulo de Ancho × Alto. Total de salas = Ancho + Alto. | Última sala: Jefe (5V) | Debes caber dentro del rectángulo. |
| **♾️ Infinito** | Ninguna | Sin final | Cada 15 salas: Jefe de Zona (5V). Vencerlo otorga **+1 Fuerza**, cura completa y **+1 HP Máx** por cada 3 jefes. |

**Retirada (solo Infinito):** Entre salas, puedes salir. Pierdes la mochila pero **conservas Fuerza y HP Máx** para la próxima sesión en esa hoja. Morir = personaje borrado.

---

## 🕹️ FLUJO DE HABITACIÓN

Tira d6 y resuelve en orden:

### 1. Tamaño
| d6 | Casillas | Sugerencia |
|:---:|:---:|:---|
| 1-2 | 3 | Pasillo 1×3 |
| 3-4 | 4 | Sala 2×2 |
| 5 | 5 | Forma L, T o cruz |
| 6 | 6 | Sala grande |

> Conéctala por una puerta de la sala anterior.

### 2. Puertas
| d6 | Salidas |
|:---:|:---:|
| 1-4 | +1 |
| 5-6 | +2 |

> Última sala de Express/Delimitado: no se tira.

### 3. Combate
| d6 | Enemigos |
|:---:|:---:|
| 1-2 | 1 |
| 3-4 | 2 |
| 5-6 | 3 |

**Resolución (turnos alternos):**

| | Éxito | Daño |
|:---|:---|:---|
| **Héroe** | 4-6 en d6 | `1 + (Fuerza - 3)` |
| **Enemigo** | 4-6 en d6 | 1 |

- **Escudo:** Absorbe automáticamente el **primer golpe** de la sala (gasta 1 uso). Una vez por sala.
- **Huir:** Gastas un **Comodín** y avanzas a la siguiente sala. **Sin botín.** El combate se aborta.

> Debes matar a todos para registrar la sala y buscar botín.

### 4. Botín (solo si ganaste el combate)
| d6 | Resultado |
|:---:|:---|
| 1-3 | No hay cofre |
| 4-6 | ¡Cofre! Tira otra vez: 1-3=Poción · 4-5=Escudo · 6=Comodín |

> Mochila llena = consume el item más antiguo para guardar el nuevo, o descarta el cofre.

---

## 👹 ESCALADO DE ENEMIGOS

### Modo Express (10 salas)

| Sala | Enemigo | Vida |
|:---:|:---|:---:|
| 1-3 | 🐛 Bicho | 1 |
| 4-6 | d6: 1-3=Bicho · 4-6=Bruto | 1-2 |
| 7-8 | 👺 Bruto | 2 |
| 9 | d6: 1-3=Bruto · 4-6=Demonio | 2-3 |
| 10 | 🐉 **Jefe Final** | **5** |

### Modos Delimitado e Infinito

| Profundidad | Enemigo                     | Vida | Notas                |
| :---------- | :-------------------------- | :--: | :------------------- |
| 1-5         | 🐛 Bicho                    |  1   | —                    |
| 6-15        | d6: 1-3=Bicho · 4-6=Bruto   | 1-2  | —                    |
| 16-25       | d6: 1-3=Bruto · 4-6=Demonio | 2-3  | —                    |
| 26-35       | 👹 Demonio                  |  3   | —                    |
| 36+         | 👹 Demonio Duro             |  3   | **Aciertan con 3-6** |

---

## 📋 REFERENCIA RÁPIDA (para post-it)

```
┌────────────────────────────────────────┐
│           BUJO DUNGEON                 │
├────────────────────────────────────────┤
│ KITS: 🛡️P·E·C  ⚔️E·E·P  🦶C·C·P  🧪P·P·E │
├────────────────────────────────────────┤
│ FLUJO (d6):                            │
│ 1.TAMAÑO: 1-2=3  3-4=4  5=5  6=6      │
│ 2.PUERTAS: 1-4=+1  5-6=+2             │
│ 3.COMBATE: 1-2=1en  3-4=2en  5-6=3en  │
│   Tú: 4-6=HIT, Daño=1+(F-3)            │
│   Enem: 4-6=1 daño  |  Escudo=1º hit   │
│   Comodín=Huye, SIN botín              │
│ 4.BOTÍN: 1-3=∅  4-6=Cofre (1-3P 4-5E 6C)│
├────────────────────────────────────────┤
│ EXPRESS: H10=Jefe(5V)                  │
│ DEL/INF: 1-5B 6-15B/Br 16-25Br/D      │
│          26-35D  36+=DD(acierta 3-6)   │
└────────────────────────────────────────┘
```

---

## 🎮 SIMULACIÓN RÁPIDA (Modo Delimitado, Kit Clásico)

```
Mapa: 12×12 → 24 salas | HP:10/10 | F:3 | Esc:3/3 | Mochila:[P][E][C][ ]
─────────────────────────────────────────────────────────
H1  Tamaño[3]=4cas  Puertas[2]=+1  Enemigos[1]=1🐛(1V)
    Turno Héroe[5]=HIT→🐛 muere.  Botín[2]=∅
    Estado: HP10 Esc3 Mochila:[P][E][C][ ]
─────────────────────────────────────────────────────────
H6  Tamaño[1]=3cas  Puertas[5]=+2  Enemigos[4]=2en
    Tipos[2,6]=🐛(1V) 👺Bruto(2V)
    T1: H[3]=Falla | Enem[5,4]=Escudo bloquea Bruto, Bicho hiere → HP9
    T2: H[6]=HIT→Bruto 1V | Enem[2,1]=Falla
    T3: H[4]=HIT→Bruto muere | Enem[6]=HP8
    T4: H[5]=HIT→Bicho muere.  Botín[4]=Cofre→[2]=Poción
    Mochila llena: consume Poción(+3HP→10), guarda nueva.
    Estado: HP10 Esc2 Mochila:[P][E][C][ ]
─────────────────────────────────────────────────────────
H18 Tamaño[5]=5cas  Puertas[1]=+1  Enemigos[6]=3en
    Tipos[4,5,6]=👺Bruto(2V) 👹Demonio(3V) 👹Demonio(3V)
    HP6, espacio reducido → ¡Gasta Comodín! Huída forzada.
    Fase 4: BLOQUEADO (sin botín por huida).
    Estado: HP6 Esc1 Mochila:[P][E][ ][ ]
─────────────────────────────────────────────────────────
H24 Tamaño[4]=4cas  Puertas=Ñ (última sala)
    JEFE 🐉 (5V). Preparación: usa Escudo de mochila → Escudo 3/3.
    T1: H[4]=HIT→J4V | J[5]=Escudo bloquea (Esc2)
    T2: H[2]=Falla | J[6]=HP5
    T3: H[5]=HIT→J3V | J[2]=Falla
    T4: H[6]=HIT→J2V | J[4]=HP4 → usa Poción → HP7
    T5: H[4]=HIT→J1V | J[1]=Falla
    T6: H[6]=HIT→¡JEFE CAE!  Botín: ∅ (sala de jefe)
─────────────────────────────────────────────────────────
    ¡VICTORIA! HP7/10 | Esc2/3 | Fuerza 3 | Mochila vacía
```
