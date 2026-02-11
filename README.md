# Chinese Checkers — INF201 Project

Functional implementation of Chinese Checkers in OCaml.

## 📚 Context

This project was developed for the INF201 course  
**Algorithms and Functional Programming**  
Université Grenoble Alpes.

The goal is to model the Chinese Checkers game and implement all core mechanics using functional programming principles.

---

## 🧠 Features

- Parameterized board dimension
- Cube-coordinate system (i, j, k) with constraint: i + j + k = 0
- Support for 1, 2, 3 or 6 players
- Turn rotation via board transformation
- Validation of:
  - Single-step moves
  - Multiple jumps
- Configuration update after each move
- Win detection
- Score computation
- Possible move generation
- Greedy strategy implementation

---

## 🏗 Architecture

### Core Types

- `case = int * int * int`
- `couleur`
- `configuration`
- `coup = Du of case * case | Sm of case list`

### Main Functional Blocks

1. Board geometry and coordinate validation
2. Configuration initialization
3. Move validation
4. Move execution
5. Game verification
6. Strategy implementation

---

## ▶️ How to Run

Compile with:

```bash
ocamlc -o dames rendu_etd.ml
