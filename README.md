Voici un README propre et professionnel pour le projet des Dames Chinoises :

---

# Chinese Checkers — INF201 Project

Functional implementation of the Chinese Checkers game in OCaml, developed for the INF201 course (Algorithms and Functional Programming).

## Project Overview

This project models and implements the Chinese Checkers board game using functional programming principles.
The board is represented using cube coordinates `(i, j, k)` satisfying the constraint `i + j + k = 0`.
The implementation supports multiple players and enforces all game rules, including move validation and win detection.

## Features

* Parameterized star-shaped board
* Cube coordinate system `(i, j, k)`
* Support for 1 to 6 players
* Turn management via board rotation
* Validation of single moves
* Validation of multiple jumps
* Configuration updates after each move
* Victory detection
* Move generation
* Greedy strategy implementation

## Project Structure

* Board geometry and coordinate validation
* Configuration initialization
* Move validation logic
* Move application and state updates
* Game verification
* Strategy computation

## How to Run

Compile with:

```bash
ocamlc -o chinese_checkers rendu_etd.ml
```

Or run with the OCaml interpreter:

```bash
ocaml rendu_etd.ml
```

If a graphical interface is provided, follow the course instructions to use it.

## Educational Objectives

* Practice functional programming in OCaml
* Work with algebraic data types
* Implement recursive functions
* Model rule-based systems
* Develop basic strategic algorithms

---

Si tu veux une version plus courte (type 10 lignes max) pour GitHub, je peux te la faire aussi.
