🧮 MatrixMaster 🔳 Advanced Matrix Calculator
Perform complex linear algebra operations with a bold, high-contrast interface ⚡
Web Application | HTML, CSS, JavaScript

---

✨ Features
✅ Multi-Operation Support – Seamlessly switch between Addition, Subtraction, Multiplication, Transpose, and Inverse calculations.
✅ Dynamic Grid Generation – Supports matrices from $1 \times 1$ up to $5 \times 5$ with real-time input field generation.
✅ Smart UI Logic – Automatically hides or shows secondary matrix inputs (Matrix B) based on the selected operation (e.g., hidden for Transpose).
✅ Error Validation – Built-in checks for square matrix requirements and non-zero determinants during Inverse operations.
✅ High-Contrast Theme – Cyberpunk-inspired aesthetic with neon green, magenta, and cyan accents for maximum readability.
✅ Precision Outputs – Automatically handles integers and rounds complex floating-point results to two decimal places.

---

🎮 Demo
Scenario: Matrix Transpose
Input Matrix A ($2 \times 3$):$$\begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix}$$
Operation: Transpose
Result: 🟢$$\begin{bmatrix} 1 & 4 \\ 2 & 5 \\ 3 & 6 \end{bmatrix}
$$Scenario: Error Handling
Input: $2 \times 3$ Matrix $\rightarrow$ Select Inverse
Output: 🔴 "ERROR: MUST BE SQUARE MATRIX!"

---

🚀 How to Use (30 seconds)
Select Operation: Click a button (ADD, SUBTRACT, etc.) from the top menu.
Define Dimensions: Enter the number of rows and columns.
Generate: Click "GENERATE MATRIX" to create the input fields.
Enter Data: Fill in the values for Matrix A (and Matrix B if applicable).
Calculate: Hit the yellow "== CALCULATE ==" bar to view your result instantly.

---

🧠 Concept
MatrixMaster is designed for engineering students and researchers who need a quick, reliable tool for linear algebra verification without the overhead of heavy software.
Linear Algebra Fundamentals: Simplifies the tedious process of manual matrix multiplication and inversion.
Responsive Design: The CSS Grid-based layout ensures the matrices remain perfectly aligned regardless of dimension.
Functional Programming: Uses JavaScript map and forEach functions to handle multidimensional array transformations efficiently.

---

⚙️ Logic Behind
Transpose Logic: Swaps row indices ($i$) with column indices ($j$) to flip the matrix over its diagonal.
Inverse Logic (2x2): Uses the determinant formula $\text{det} = ad - bc$. If $\text{det} \neq 0$, it applies the adjugate matrix method.
Arithmetic: Maps through the nested arrays of Matrix A and B to perform element-wise calculations.

---

🎯 Use Case
Engineering Homework: Checking results for 2D transformations or stress-strain tensors.
Coding Reference: Visualizing how matrix data structures behave before implementing them in C++ or Python.
Quick Checks: Validating determinants and inverses during exam preparation.
Bold Design → Precision Calculations


Swayam Waghdhare, F.E., B.Tech, Mechanical, TCET Mumbai
