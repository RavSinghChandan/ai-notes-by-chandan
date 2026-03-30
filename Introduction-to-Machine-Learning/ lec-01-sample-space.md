# 📌 Topic: Matrix Fundamentals (Linear Algebra)

## 🔹 Core Idea
- Matrix = Structured way to store data (rows + columns)
- Rows = Data points (samples)
- Columns = Features (variables)
- Foundation of all ML computations

## 🔹 Key Concepts
- Matrix Dimension → m × n (rows × columns)
- Transpose (Aᵀ) → converts rows into columns
- Matrix Multiplication → row × column interaction
- Identity Matrix (I) → no change transformation
- Square Matrix → rows = columns

## 🔹 Key Properties
- A(BC) = (AB)C → Associative
- A(B + C) = AB + AC → Distributive
- AB ≠ BA → Not commutative (IMPORTANT)

## 🔹 Key Formula
- Aᵀ → (n × m)
- (AB)ᵀ = Bᵀ Aᵀ
- A × I = A

## 🔹 Special Matrices
- Diagonal Matrix → non-diagonal = 0
- Orthogonal Matrix → A Aᵀ = I
- Idempotent Matrix → A² = A
- Nilpotent Matrix → Aᵏ = 0

## 🔹 Example
Matrix A (2×3):
[1 2 3]
[4 5 6]

Transpose Aᵀ (3×2):
[1 4]
[2 5]
[3 6]

## 🔹 ML Mapping
- Matrix = Dataset
- Rows → Observations
- Columns → Features
- XW → Prediction (core ML equation)
- Neural networks = multiple matrix multiplications

## 🔹 Intuition (VERY IMPORTANT)
- Matrix = Data
- Multiplication = Learning
- Transpose = Changing perspective

## 🔹 Tricks (🔥 Interview + Fast Recall)
- Always check dimensions before multiplication
- If dimensions don’t match → multiplication NOT possible
- Remember: (AB)ᵀ reverses order → Bᵀ Aᵀ
- Identity matrix = behaves like number 1
- If stuck → think in terms of rows & columns interaction

## 🔹 Common Mistakes
- Thinking AB = BA ❌
- Forgetting dimension mismatch
- Ignoring transpose order

## 🔹 Interview Questions
- What is a matrix?
- What is transpose and why is it used?
- Why is matrix multiplication not commutative?
- Explain matrix multiplication with example
- How are matrices used in ML?

## 🔹 Golden Insight
- “Machine Learning = Matrix Operations on Data”