---
title: Scientific programming languages
date: 2025-04-16
--- 

In computer programming, a scientific programming language can refer to two degrees of the same concept.

In a broad sense, a scientific programming language is a programming language that is widely used in computational science and computational mathematics.

In this sense, C/C++ and Python can be considered as scientific programming languages. In a stricter sense, a scientific programming language is a language that is designed and optimized to use mathematical formulas and matrices. Such languages are characterized not only by the presence of libraries that perform mathematical or scientific functions, but also by the syntax of the language itself. For example, neither C++ nor Python have built-in matrix types or functions for matrix arithmetic (addition, multiplication, etc.); instead, this function is available through standard libraries. Scientific programming languages in a strong sense include ALGOL , APL, Fortran, J , Julia, Maple, MATLAB , and R.

Scientific programming languages should not be confused with scientific language in general, which loosely refers to the higher standards of accuracy, correctness, and brevity expected of practitioners of the scientific method.

Examples Linear Algebra Scientific programming languages provide opportunities for working with linear algebra. For example, the following Julia program solves a system of linear equations :

A = rand(20, 20) # A is a 20x20 matrix

b = rand(20) # b is a 20-element vector

x = A\b # x is the solution to A*x = b

Working with large vectors and matrices is a key feature of these languages, as linear algebra lays the foundation for mathematical optimization, which, in turn, allows for basic applications such as deep learning.

Mathematical optimization In a scientific programming language, we can calculate the optimum of a function with a syntax close to the mathematical language. For example, the following Julia code finds the minimum of a polynomial.

using Optim

P(x,y) = x2 - 3x*y + 5y2 - 7y + 3

z₀ = [ 0.0

0.0 ] # starting point for optimization algorithm o

ptimize(z -> P(z…), z₀, Newton();

autodiff = :forward)

This example uses Newton's minimization method. Modern scientific programming languages will use automatic differentiation to calculate gradients and hessians of a function given as input; cf. differentiable programming. Here, automatic direct differentiation is selected for this task. Old scientific programming languages, such as the venerable Fortran, would require the programmer to pass next to the function to be optimized, a function that calculates the gradient, and a function that calculates the hessian.

The more knowledge you have about the function that needs to be minimized, the more efficient algorithms you can use. For example, convex optimization provides faster computations when the function is convex, quadratic programming provides faster computations when the function is at most quadratic in its variables, and linear programming when the function is maximally linear.






































