# 🚀 Codetantra C++ Laboratory

![Language](https://img.shields.io/badge/Language-C++-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Codetantra-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

A curated collection of **C++ programming solutions for Codetantra laboratory exercises and assignments**.  
This repository aims to help students understand **core programming concepts, improve logical thinking, and prepare effectively for Codetantra lab sessions**.

---

## 📌 Table of Contents

- 📖 About the Project  
- ✨ Key Features  
- 📂 Repository Structure  
- 🧠 Concepts Covered  
- ⚙️ Getting Started  
- 💡 Example Program  
- 🤝 Contributing  
- 📜 License  
- 👨‍💻 Author  

---

## 📖 About the Project

The **Codetantra C++ Laboratory Repository** contains solutions to commonly assigned programming problems used in Codetantra labs.

The primary goal of this project is to provide:

- Clear and beginner-friendly C++ programs  
- Well-structured coding examples  
- Practice material for lab exercises  
- A quick reference for programming fundamentals  

This repository can serve as a **learning resource for beginners and a revision guide for students preparing for lab evaluations**.

---

## ✨ Key Features

- 📚 Beginner-friendly code implementation  
- 🧠 Focus on logical problem solving  
- 📂 Organized programming examples  
- ⚡ Easy-to-run programs  
- 🎓 Useful for Codetantra lab preparation  

---

## 📂 Repository Structure

codetantra_cpp/
│
├── arrays/
│ └── array_example.cpp
│
├── loops/
│ ├── fibonacci.cpp
│ └── factorial.cpp
│
├── patterns/
│ ├── pattern1.cpp
│ └── pattern2.cpp
│
├── functions/
│ └── nCr.cpp
│
└── README.md


Each folder contains programs categorized by **specific C++ programming concepts**.

---

## 🧠 Concepts Covered

The repository includes programs based on:

- Variables and Data Types  
- Input / Output  
- Conditional Statements  
- Loops (`for`, `while`)  
- Arrays  
- Functions  
- Pattern Printing  
- Mathematical Computations  

---

## ⚙️ Getting Started

Follow these steps to run the programs on your system.

### 1️⃣ Clone the repository

git clone https://github.com/manjeetkeshrihkp/codetantra_c.git

cd codetantra_c

### 3️⃣ Compile a program
g++ filename.cpp

### 4️⃣ Run the program

./a.out

---

## 💡 Example Program


Fibonacci Series in C++

#include <iostream>
using namespace std;

int main() {
    int n = 10, a = 0, b = 1, next;

    cout << "Fibonacci Series:" << endl;

    for(int i = 0; i < n; i++) {
        cout << a << " ";
        next = a + b;
        a = b;
        b = next;
    }

    return 0;
}


🤝 Contributing

Contributions, issues, and feature requests are welcome!

If you would like to contribute:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeature).

Open a Pull Request.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Author
Manjeet Keshri

GitHub: @manjeetkeshrihkp

⭐ If you found this repository helpful, please consider giving it a star!
