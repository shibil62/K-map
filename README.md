# 🧩 K-Map Solver

<p align="center">
  An interactive Karnaugh Map solver for simplifying Boolean expressions using SOP and POS.
</p>

<p align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</p>

<p align="center">
  <b>Interactive • Visual • Responsive • Educational</b>
</p>

---

## 📖 About The Project

**K-Map Solver** is an interactive web application designed to simplify Boolean expressions using **Karnaugh Maps (K-Maps)**.

Instead of only displaying the final Boolean expression, the application provides a complete visual representation of the solution, including the **Karnaugh Map, optimal groupings, simplified expression, logic circuit, and truth table**.

The project supports both **SOP (Sum of Products)** and **POS (Product of Sums)** forms and is designed to make K-Map simplification easier to understand for students.

---

## ✨ Features

### 🔢 Variable Support

- Supports **2-variable K-Maps**
- Supports **3-variable K-Maps**
- Supports **4-variable K-Maps**
- Custom variable names

### 🧮 Boolean Expression Simplification

- Automatic Boolean expression minimization
- **SOP (Σ / Sum of Products)** support
- **POS (Π / Product of Sums)** support
- Finds optimized groupings automatically
- Prioritizes simplified expressions with fewer groups and literals

### 🗺️ Interactive Karnaugh Map

- Automatically generates the appropriate K-Map
- Uses **Gray Code ordering**
- Visually highlights K-Map groups
- Supports multiple valid optimal grouping solutions
- Clearly displays minterm/maxterm positions

### 🔄 Wrap-Around Grouping

Karnaugh Maps allow cells on opposite edges to be grouped together.

This project includes:

- Wrap-around grouping detection
- Visual group highlighting
- Fold animation to help visualize edge-to-edge grouping

Because apparently K-Maps weren't confusing enough already 😭

### ❌ Don't Care Terms

The solver supports optional **Don't Care (X)** terms.

Features include:

- Toggle Don't Care mode on/off
- Automatically uses Don't Care cells when beneficial
- Uses them to create larger groups when possible
- Shows which Don't Care terms were used in the solution

### 🔌 Logic Circuit Generation

The application automatically generates a visual logic circuit for the simplified Boolean expression.

Supported components include:

- AND gates
- OR gates
- NOT gates
- Direct input connections

The generated circuit automatically adapts depending on whether the expression is in **SOP or POS form**.

### 📊 Truth Table

A complete truth table is generated automatically.

It includes:

- Decimal term numbers
- Input variable values
- Output values
- Don't Care states represented as `X`

### 🎲 Random Examples

Click the **Random Example** button to generate a new Boolean function instantly.

Useful for:

- Practicing K-Map solving
- Testing the solver
- Learning different grouping possibilities

### 🌙 Light & Dark Mode

The website supports:

- ☀️ Light Mode
- 🌙 Dark Mode

Your selected theme is stored locally in the browser.

### 📱 Responsive Design

The application is designed to work across different screen sizes:

- 💻 Desktop
- 📱 Mobile
- 🖥️ Larger screens

The interface includes touch-friendly controls and responsive layouts.

---

## 🛠️ Built With

<p>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</p>

| Technology | Purpose |
|---|---|
| 🟠 **HTML5** | Application structure |
| 🔵 **CSS3** | Styling, responsiveness, animations, and themes |
| 🟡 **JavaScript** | K-Map generation, Boolean minimization, logic processing, and UI interactions |

> No frameworks. No backend. Just **HTML, CSS, and JavaScript** doing the heavy lifting. 💪

---

## 🚀 Getting Started

No installation or dependencies are required.

You can simply open:

```text
index.html
```

in any modern web browser.

---

## 🧠 How To Use

### 1️⃣ Select the Number of Variables

Choose between:

- 2 Variables
- 3 Variables
- 4 Variables

### 2️⃣ Enter Variable Names

Customize the variables used in the Boolean function.

Example:

```text
F(A, B, C, D)
```

### 3️⃣ Choose SOP or POS

Switch between:

```text
Σ → SOP (Sum of Products)
```

and:

```text
Π → POS (Product of Sums)
```

### 4️⃣ Enter the Terms

Enter:

- **Minterms** for SOP
- **Maxterms** for POS

Example:

```text
F(A, B, C, D) = Σ(5, 7, 13, 15)
```

### 5️⃣ Add Don't Care Terms (Optional)

Enable the **Don't Care** option and enter the required terms.

The solver automatically determines whether they can be used to create better groupings.

### 6️⃣ Show the Answer

Click **Show Answer**.

The application will generate:

- 🗺️ Karnaugh Map
- 🎨 Optimal groupings
- 🧮 Simplified Boolean expression
- 🔌 Logic circuit
- 📊 Truth table

---

## 📂 Project Structure

```text
K-map/
│
├── index.html
└── README.md
```

The entire application is contained in a **single HTML file**, making it easy to run, share, and deploy.

---

## 🧠 How It Works

The solver follows these general steps:

1. Reads the selected variables and terms
2. Generates the appropriate Karnaugh Map
3. Arranges cells using Gray Code ordering
4. Identifies valid groups
5. Finds optimized combinations
6. Generates the simplified Boolean expression
7. Displays visual groupings
8. Creates the corresponding logic circuit
9. Generates the truth table

The solver can also detect **multiple equally optimal grouping solutions** and allows users to switch between them.

---

## 🌐 Deployment

Since this is a static website, it can be deployed easily using:

- GitHub Pages
- Netlify
- Vercel
- Any static web hosting provider

---

## 🔮 Future Improvements

- [ ] Step-by-step K-Map solving explanation
- [ ] Manual grouping mode
- [ ] Grouping validation for students
- [ ] Practice mode
- [ ] Difficulty levels
- [ ] Save K-Map questions
- [ ] Shareable solutions
- [ ] Export results as PDF
- [ ] More detailed simplification explanations

---

## 🎯 Why This Project?

Karnaugh Maps can be confusing, especially when dealing with:

- Wrap-around grouping
- Multiple valid solutions
- Don't Care conditions
- SOP and POS forms
- Logic circuit implementation

This project aims to make the process more **visual, interactive, and easier to understand**.

```text
Boolean Function
        ↓
   Karnaugh Map
        ↓
 Optimal Grouping
        ↓
Simplified Expression
        ↓
   Logic Circuit
```

---

## 👨‍💻 Author

**Shibil P A**

Created as an interactive educational project for learning and visualizing **Karnaugh Map simplification and Boolean logic**.

### 🔗 Repository

[github.com/shibil62/K-map](https://github.com/shibil62/K-map/blob/main/README.md)

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a **star** ⭐.

<p align="center">
  Made with ❤️ and a questionable amount of Boolean algebra.
</p>
