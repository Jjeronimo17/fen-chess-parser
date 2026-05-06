
---

# ♟️ Final Practice – FEN Parser & Chessboard Engine

## 📌 Project Overview

This project was developed as a final assignment for a coding class. The main goal was to design and implement a **custom chessboard engine from scratch** capable of:

* Parsing a **FEN (Forsyth-Edwards Notation) string**
* Interpreting its data
* Representing the game state programmatically on a chessboard

A FEN string encodes a complete snapshot of a chess game at a specific moment, including:

* Piece placement
* Active player (turn)
* Castling rights
* En passant target square
* Halfmove clock
* Fullmove number

This project focuses on correctly reading and transforming that information into a structured and usable internal representation.

---

## 🧠 What This Project Does

✔️ Reads a FEN string
✔️ Parses each section of the notation
✔️ Builds a chessboard model from scratch
✔️ Places pieces correctly on the board
✔️ Identifies whose turn it is
✔️ Stores additional game-state metadata

---

## 🏗️ Project Structure

Although the internal structure may evolve, the project is conceptually divided into:

* **FEN Parser Module**

  * Responsible for reading and splitting the FEN string
  * Validates and interprets each section

* **Chessboard Representation**

  * Custom implementation of a chessboard (likely 8x8 matrix or equivalent)
  * Handles piece placement and board state

* **Piece Modeling**

  * Representation of different chess pieces
  * Possibly using enums, classes, or inheritance

* **Game State Handler**

  * Stores turn, castling rights, and other metadata

---

## ⚙️ Technologies Used

* **IDE:** IntelliJ IDEA

* **Language & SDK:** OpenJDK 24.0.1

* **Documentation Source:**

  * [FEN Specification (Chess Programming Wiki)](https://www.chessprogramming.org/Forsyth-Edwards_Notation)

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Jjeronimo17/FinalPractice.git
   ```

2. Open the project in **IntelliJ IDEA**

3. Make sure the SDK is set to:

   ```
   OpenJDK 24.0.1
   ```

4. Run the main class to test the parser with a FEN string

---

## 🧪 Example

Example of a FEN string:

```
rnbqkb1r/pppppppp/5n2/8/8/5N2/PPPPPPPP/RNBQKB1R w KQkq - 0 1
```

This represents:

* Standard starting structure (with slight modification)
* White to move (`w`)
* Full castling rights (`KQkq`)
* No en passant target (`-`)
* Move counters (`0 1`)

---

## 🎯 Learning Objectives

Through this project, we developed skills in:

* Parsing structured text data
* Object-oriented programming
* Data modeling
* Problem decomposition
* Working with real-world notation systems (like FEN)
* Understanding chess logic at a technical level

---

## 👨‍💻 Authors

* **Jeronimo Jaramillo Agudelo**
* **Juan Esteban Grisales Restrepo**

---

## 🏫 Academic Context

* **University:** EAFIT
* **Course:** Programming / Software Development
* **Date:** March 11, 2025

---

## 💡 Possible Future Improvements

* Move validation system
* Chess game simulation
* Better GUI (Graphical User Interface)
* Support for PGN parsing
* AI-based move suggestions

---
