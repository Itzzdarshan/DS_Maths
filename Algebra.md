
Linear Algebra for Machine Learning

Linear Algebra is the mathematical backbone of Machine Learning.

Why Linear Algebra Is Important for ML?
It is the language of Machine Learning.

In ML:

• Datasets → stored as matrices
• Features → represented as vectors
• Model calculations → done using matrix operations

What Are “Weights” in ML?

Weights are numbers that tell the model how important each feature is when making predictions.

Important points:

• Weights are learned automatically during training
• Model adjusts weights to reduce error
• Large weight → feature is very important
• Small weight → feature is less important

Example:
House Price = (Size × w₁) + (Location × w₂)

Here:
w₁, w₂ = weights

⸻

Scalars, Vectors, and Matrices

Scalar

A single numerical value.
Example:
5, 0.01, −3

In ML: Used for learning rate, weights, bias, etc.

Vector

A list of numbers (1D data).

Example:
(2, 3, 5) → 3D vector
(2, 3, 6, 7, 8, 1) → High-dimensional vector

In ML: Each data point is represented as a vector.

Matrix

Collection of vectors (2D data).

Used to store:
• Datasets
• Images
• Model parameters


High Dimensional Interpretation

Dimensions = number of features.

Example:
(2,3,6,7,8,1) → 6 features

In real ML: Datasets may have hundreds or thousands of dimensions.


Basic Linear Algebra Operations

1️⃣ Addition & Subtraction

Combine vectors or matrices of same shape.
Used when updating weights.

2️⃣ Scalar Multiplication

Multiply every value by a scalar.
Used to control learning speed.

3️⃣ Dot Product (Core ML operation)

Multiplies vectors and sums results.

Used in:
• Predictions
• Neural networks
• Linear regression

4️⃣ Cross Product

Mainly used in physics / geometry (less common in ML).

5️⃣ Transpose

Turns rows into columns.

Matrix shape changes:
2×3 → 3×2

Used heavily in ML calculations.

Linear Algebra in ML 
Linear Algebra gives ML the ability to see, calculate, and learn from data.
