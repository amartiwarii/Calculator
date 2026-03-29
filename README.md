# Python Tkinter Calculator

A desktop calculator application built using **Python** and the **Tkinter GUI framework**. This program provides a graphical interface that allows users to perform basic arithmetic calculations along with square and square root operations.

The project demonstrates how to build a simple GUI-based application in Python using object-oriented programming and Tkinter widgets.

---

## Features

* Graphical calculator interface
* Basic arithmetic operations

  * Addition (+)
  * Subtraction (-)
  * Multiplication (×)
  * Division (÷)
* Square function (x²)
* Square root function (√x)
* Clear button to reset expressions
* Keyboard input support
* Dynamic display for current and total expressions

---

## Technologies Used

* Python
* Tkinter (Python's built-in GUI library)

No external libraries are required.

---

## Project Structure

```
calculator/
│
├── main.py
└── README.md
```

`main.py` contains the full source code for the calculator application.

---

## Requirements

* Python 3.7 or later

Tkinter is included with most Python installations. If it is missing, install it using your system’s package manager.

Example for Ubuntu/Linux:

```
sudo apt install python3-tk
```

---

## Installation

1. Clone the repository

```
git clone https://github.com/amartiwarii/Calculator.git
```

2. Navigate to the project directory

```
cd Calculator
```

3. Verify Python installation

```
python --version
```

---

## Running the Application

Run the calculator with the following command:

```
python main.py
```

A calculator window will open on your screen.

---

## How to Use

1. Click the digit buttons to enter numbers.
2. Select an operator (+, −, ×, ÷).
3. Press **=** to evaluate the expression.
4. Use **C** to clear the current calculation.
5. Use **x²** to square the current number.
6. Use **√x** to compute the square root.

### Keyboard Shortcuts

| Key   | Action              |
| ----- | ------------------- |
| 0–9   | Enter digits        |
| +     | Addition            |
| -     | Subtraction         |
| *     | Multiplication      |
| /     | Division            |
| Enter | Evaluate expression |

---

## Example

Input:

```
8 + 2 * 5
```

Output:

```
18
```

---

## Learning Objectives

This project demonstrates:

* Building desktop graphical interfaces with Tkinter
* Using object-oriented programming for GUI applications
* Event handling and keyboard bindings
* Button layout using Tkinter's grid system
* Expression evaluation in Python

---

## Possible Improvements

* Add scientific calculator functions
* Improve UI styling and themes
* Add calculation history
* Replace `eval()` with a safer expression parser
* Improve handling of long expressions

---

## License

This project is licensed under MIT License.