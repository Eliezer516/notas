---
telegraph_page_url: https://telegra.ph/BuJo-Dungeon-06-26
telegraph_page_path: BuJo-Dungeon-06-26
---
 Aquí tienes el manual corregido con el **cofre siempre abierto** (sin tirada de cerrado) y el flujo de juego actualizado:

---

# 🏰 BuJo Dungeon
**Dungeon-crawler táctico para tu libreta de puntos**

Necesitas: un d6, lápiz, borrador y cuaderno cuadriculado/punteado.

---

## 👤 FICHA DEL HÉROE

```
VIDAS:    [❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️] 10/10        FUERZA: 3  (Daño = 1 + Fuerza - 3)
ESCUDO:   [🛡️🛡️🛡️] 3/3 usos                  MOCHILA: [____] [____] [____] [____]
```

**Kits de Inicio** (elige uno, inmutable durante la partida):

| Kit | Contenido | Estilo |
|:---:|:---|:---|
| 🛡️ **Clásico** | Poción · Escudo · Comodín · Vacío | Equilibrado |
| ⚔️ **Guerrero** | Escudo · Escudo · Poción · Vacío | Tanque (sin escape) |
| 🦶 **Explorador** | Comodín · Comodín · Poción · Vacío | Evasivo (sin reparar escudo) |
| 🧪 **Alquimista** | Poción · Poción · Escudo · Vacío | Supervivencia (sin escape) |

> **Items:**  
> **Poción** → Cura 3 HP. **Acción rápida** entre habitaciones; en combate, **consume tu turno**.  
> **Escudo** → Repara tu escudo equipado a 3/3. Solo usable **entre habitaciones** o **cuando tu escudo equipado está en 0/3**.  
> **Comodín** → Escapa de una habitación tras ver enemigos (Fase 3) pero antes del primer turno de combate. **Sin botín, -1 HP.**  
> **Vacío** → Se rellena con el primer cofre que encuentres. Puedes **ignorar** cofres voluntariamente.

> **Mochila llena:** Elige un item para descartar (o consumir si es Poción/Escudo) antes de guardar el nuevo.

---

## 🎮 MODOS DE JUEGO

| Modo | Preparación | Final | Notas |
|:---|:---|:---|:---|
| **⏱️ Express** | Ninguna | Habitación 10: Jefe (5V) | 10 minutos. Ideal para primeras partidas. |
| **🗺️ Delimitado** | Dibuja rectángulo Ancho×Alto. Salas = Ancho + Alto. | Última sala: Jefe (5V) | Debes caber dentro. Si una sala no cabe, es **derrumbada** (ver regla abajo). |
| **♾️ Infinito** | Ninguna | Sin final | Cada 15 salas: Jefe de Zona (5V). Vencerlo → **+1 Fuerza**, cura completa, **+1 HP Máx** por cada 3 jefes. |

**Retirada (solo Infinito):** Entre salas, sal de la mazmorra. Pierdes la mochila pero **conservas Fuerza y HP Máx** para la **misma hoja física**. Nueva hoja = personaje nuevo. Morir = borrado permanente.

---

## 🕹️ FLUJO DE JUEGO COMPLETO

```
1. Elige modo de juego y kit de inicio. Dibuja ficha del héroe.
2. Dibuja habitación de entrada (3 casillas). Coloca 1 puerta de salida.
3. Entras por la puerta de entrada.
4. Tira d6 → Tamaño (Tabla S). Dibuja habitación en cuadrícula.
5. Tira d6 → Puertas adicionales. Coloca (máximo las que quepan en márgenes).
6. Tira d6 → Enemigos. Coloca en habitación (tú eliges dónde).
7. Resuelve combate o usa Comodín para huir (pierdes 1 Vida, sin botín).
8. Tira d6 → ¿Cofre? Si.
9. Si ganaste combate, abre cofre si hay. Tira contenido:
   1 = 💥 Trampa (-1 HP)
   2-3 = Poción
   4-5 = Escudo (repara escudo equipado inmediatamente si está gastado;
         si está en 3/3, guarda item en mochila)
   6 = Comodín
   Puedes ignorar el cofre voluntariamente.
10. Elige puerta de salida. Vuelve a 4.
11. Última habitación del modo = JEFE (5 Vidas). Mata o muere.
```

---

## 📊 TABLAS

### Tabla S: Tamaño de Sala

| d6 | Casillas | Sugerencia |
|:---:|:---:|:---|
| 1-2 | 3 | Pasillo 1×3 |
| 3-4 | 4 | Sala 2×2 |
| 5 | 5 | Forma L, T o cruz |
| 6 | 6 | Sala grande |

> Conéctala por una puerta de la sala anterior.

**Regla de derrumbe (Delimitado):** Si el tamaño no cabe en el espacio restante del rectángulo, dibuja lo que quepa. La sala es **derrumbada**: sin puertas extra, sin botín, y combate con **-1 enemigo** (mínimo 1).

### Tabla P: Puertas

| d6 | Salidas |
|:---:|:---:|
| 1-4 | +1 |
| 5-6 | +2 |

> Última sala de Express/Delimitado: no se tira. Puertas que no quepan en el margen se ignoran.

### Tabla E: Enemigos

| d6 | Cantidad |
|:---:|:---:|
| 1-2 | 1 |
| 3-4 | 2 |
| 5-6 | 3 |

### Combate (turnos alternos)

| | Éxito | Daño |
|:---|:---|:---|
| **Héroe** | 4-6 en d6 | `1 + (Fuerza - 3)` |
| **Enemigo** | 4-6 en d6 | 1 |

- **Escudo:** Absorbe automáticamente el **primer golpe** de la sala (gasta 1 uso). Una vez por sala.
- **Huir:** Gastas un **Comodín** tras ver enemigos pero antes del primer turno. **-1 HP, sin botín.**

> Debes matar a todos para registrar la sala y buscar botín.

### Tabla C: ¿Cofre?

| d6 | Resultado |
|:---:|:---|
| 1-3 | No hay cofre |
| 4-6 | ¡Cofre abierto! (se abre tras combate) |

### Tabla CC: Contenido del Cofre

| d6 | Resultado |
|:---:|:---|
| 1 | **💥 Trampa!** -1 HP. No guardas nada. |
| 2-3 | **Poción** |
| 4-5 | **Escudo** → Repara escudo equipado a 3/3 inmediatamente si tiene usos gastados; si está en 3/3, guarda item en mochila. |
| 6 | **Comodín** |

> Puedes **ignorar el cofre voluntariamente** si no quieres arriesgarte o tu mochila está llena.

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

| Profundidad | Enemigo | Vida | Notas |
|:---|:---|:---:|:---|
| 1-5 | 🐛 Bicho | 1 | — |
| 6-15 | d6: 1-3=Bicho · 4-6=Bruto | 1-2 | — |
| 16-25 | d6: 1-3=Bruto · 4-6=Demonio | 2-3 | — |
| 26-35 | 👹 Demonio | 3 | — |
| 36+ | 👹 Demonio Duro | 3 | **Acierta con 3, 4, 5 o 6** (4/6 de probabilidad) |

---

## 📝 NOTAS DE DISEÑO

- **Cofre siempre abierto:** El cofre está visible y accesible, pero solo se puede interactuar con él tras limpiar la sala de enemigos. Si huyes con Comodín, el cofre queda atrás sin poder ser abierto.
- **Escudo de cofre vs. Escudo equipado:** El item "Escudo" en mochila es un **repuesto**. El escudo equipado [🛡️🛡️🛡️] es tu protección activa. Cuando usas el item, reparas el activo. Si el activo ya está en 3/3, el item se guarda como objeto consumible para más tarde.
- **Penalización de huida (-1 HP):** El Comodín ya no es escape gratis. Fuerza al jugador a pesar riesgo vs. recurso.