# Calculator

A feature-rich, interactive command-line calculator written in C. It supports basic arithmetic, advanced scientific operations, trigonometric calculations, and a fully functional quadratic equation solver that handles both real and complex roots.

---

## Features

* **Basic Arithmetic:** Addition, Subtraction, Multiplication, and Division (with zero-division protection).
* **Scientific Functions:** Power calculation (`pow`) and Square Root (`sqrt`).
* **Factorial Calculation:** Computes factorials for positive integers using `unsigned long long` to handle larger numbers.
* **Logarithm:** Base-10 logarithm calculations (`log10`).
* **Trigonometry:** Sine, Cosine, and Tangent calculations (takes inputs in degrees and automatically converts them to radians).
* **Quadratic Equation Solver:** Solves equations of the form $ax^2 + bx + c = 0$, handling equal roots, distinct real roots, and complex/imaginary roots.
* **Interactive Loop:** Runs continuously until you choose to exit.

---

## Prerequisites

To compile and run this program, you will need a C compiler installed on your system (such as **GCC**).

---

## How to Build and Run

1. Clone or download the `Calculator code` file to your local machine.
2. Open your terminal and navigate to the directory where the file is saved.
3. Compile the code using **GCC**. *Note: The math library flag (`-lm`) is required.*

```bash
gcc Calculator_code -o Calculator_code-lm

```

4. Run the executable:

```bash
./Calculator_code

```

---

## Menu Options

```text
------------------ CALCULATOR ------------------
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Power
6. Factorial
7. Square Root
8. Logarithm (base 10)
9. Sin
10. Cos
11. Tan
12. Roots of quadratic equation
13.Addition of matrices
14.Subtraction of matrices
15.Matrix multiplication
0. Exit

```

---

## Author

Created as a practice project for learning C programming, control structures, and the standard math library.
