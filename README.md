# Tic-Tac-Toe (Tres en raya) — Python
```
+-------+-------+-------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   4   |   X   |   6   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-------+-------+-------+
Ingresa tu movimiento (1-9):
```

Proyecto final del curso **PCEP – Certified Entry-Level Python Programmer** (OpenEDG Python Institute).

Juego de tres en raya por consola desarrollado en Python. El usuario juega con O y la máquina con X. La máquina siempre coloca la primera X en el centro y elige sus movimientos de forma aleatoria.

---

## 🛠️ Stack Técnico
* **IDE:** Visual Studio Code
* **Lenguaje:** Python 3
* **Modulos:** `random` (módulo estándar de Python)
* **Control de Versiones:** Git & GitHub

## 📄 Conceptos aplicados
* Listas bidimensionales — el tablero se representa como una lista de listas `tablero[fila][columna]`
* Funciones con parámetros, retorno de valores y docstrings
* Bucles while y control de flujo con `break y `continue
* Módulo `random` — función `randrange()` para movimientos aleatorios de la máquina
* Validación de entrada del usuario
* Operadores aritméticos para conversión de índice a coordenadas (`//` y `%`)

## 📂 Estructura del Proyecto
```
tic_tac_toe.py          ← Programa principal con toda la lógica del juego
```

## 🚀 Funciones principales
| Función | Descripción |
| :--- | :--- |
| `mostrar_tablero(tablero)` | Dibuja el estado actual del tablero en consola |
| `introducir_movimiento(tablero)` | Solicita y valida el movimiento del usuario (1-9) |
| `obtener_casillas_libres(tablero)` | Devuelve lista de tuplas con posiciones libres |
| `comprobar_victoria(tablero, simbolo)` | Comprueba filas, columnas y diagonales en busca de ganador |
| `movimiento_maquina(tablero)` | Elige aleatoriamente una casilla libre y coloca `X` |

## 📐 Reglas del juego
* La máquina juega con `X`, el usuario con `O`
* La máquina siempre empieza colocando `X` en el centro
* Los cuadros se numeran del 1 al 9
* La máquina elige su movimiento de forma aleatoria
* El juego termina cuando hay un ganador o se agotan las casillas (empate)

## ⚙️Instalación y ejecución

### Requisitos previos
- Python 3

### 1. Clonar el repositorio
```bash
git clone https://github.com/jorge-martin-perez/tic-tac-toe-python.git
```

### 2. Ejecutar el programa
```bash
python tic_tac_toe.py
```

### 3. Ejemplo de partida
```
+-------+-------+-------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   4   |   X   |   6   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-------+-------+-------+
Ingresa tu movimiento (1-9):
```
