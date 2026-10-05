# 🚀 C++ Fundamentals & Interactive Practice

A structured repository documenting my journey learning C++ core programming principles, memory handling basics, stream I/O, and arithmetic operations using online compilers and real-time verification labs.

---

## 💡 Knowledge Gained

* **Standard Input/Output Streams (`<iostream>`):** Mastering stream output (`std::cout`), stream input (`std::cin`), string insertion operators (`<<`), and line formatting (`\n`).
* **Variable Declarations & Data Types:** Understanding memory storage types including integers (`int`) for whole numbers, floating-point numbers (`double`) for decimal accuracy, and string literals.
* **Basic Arithmetic Operations:** Implementing addition (`+`), subtraction (`-`), multiplication (`*`), and standard arithmetic expressions directly within execution code.
* **Console User Interaction:** Building interactive command-line programs that take dynamic input from a user, process data in memory, and display computed outputs.

---

## 🛠️ Skills Acquired

* **C++ Syntax Setup:** Structuring standard boilerplate code using `#include <iostream>`, entry point function `int main()`, and clean termination via `return 0;`.
* **Variable Initialization & Reassignment:** Storing initial values in variables and mutating/updating existing variables dynamically without re-declaring types.
* **Input Validation & Formatting:** Properly separating string labels from numerical variable output to maintain clean console readable outputs.
* **Code Debugging & Execution:** Running code via online compilers (OneCompiler) and iteratively testing outputs against targeted programming prompts.

---

## 📁 Exercises & Code Examples

### 1. Simple Addition Calculator
Prompts the user for two integers and outputs their sum:

```cpp
#include <iostream>

int main() {
    std::cout << "my first calculater \n";
    int firstnumber, secondnumber;
    int sum;

    std::cout << "inpute one \n";
    std::cin >> firstnumber;

    std::cout << "inpute two \n";
    std::cin >> secondnumber;

    sum = firstnumber + secondnumber;

    std::cout << "answer: \n" << sum;

    return 0;
}
