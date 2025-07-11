# ATM-Login
# 🔁 Higher-Order Functions in Python

This project demonstrates how to build and use **Higher-Order Functions (HOFs)** in Python. Inspired by Codecademy's "Create Your Own Higher-Order Function" project, it provides hands-on experience writing functions that:

- Accept other functions as arguments (callbacks)
- Return functions as results (function factories)

You'll also explore Python’s built-in functional programming tools such as `map()`, `filter()`, and `reduce()` — and test your work using `unittest`.

---

## 🚀 Features

- ✅ `custom_map()` — your own implementation of `map()`
- ✅ `create_multiplier()` — returns a new function on-the-fly
- ✅ Functional programming tools: `map()`, `filter()`, `reduce()`
- ✅ Comprehensive unit testing with `unittest`
- ✅ Clean and reusable function design

---

## 🧠 Key Concepts

- **Higher-Order Functions**
- **First-Class Functions**
- **Function Factories**
- **Lambda Functions**
- **Code Modularity and Reusability**
- **Testing Functional Behavior**

---

## 📁 File Structure

higher_order_functions/
├── higher_order_functions.py # Core logic & main script
├── test_higher_order_functions.py # Unit tests using unittest
└── README.md # Project documentation

yaml
Copy
Edit

---

## 📌 Example Output

When you run `higher_order_functions.py`:

Original: [1, 2, 3, 4, 5]
Squared: [1, 4, 9, 16, 25]
Names starting with A: ['Alice', 'Anna']
Total Sum: 15
Doubled (custom_map): [2, 4, 6, 8, 10]
Tripled (create_multiplier): [3, 6, 9, 12, 15]

yaml
Copy
Edit

---

## 🧪 Running the Project

### ▶ Run the Main Script:

```bash
python higher_order_functions.py
🧪 Run Unit Tests:
bash
Copy
Edit
python test_higher_order_functions.py
Or using the unittest discovery command:

bash
Copy
Edit
python -m unittest discover