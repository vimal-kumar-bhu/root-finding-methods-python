# Root-Finding Methods in Python

This repository contains Python implementations of **common root-finding methods** used in numerical analysis and scientific computing.  
All methods include:
- Function implementation
- Error table using pandas
- Function & root plot using matplotlib
- Error convergence plot

---

## Methods Implemented

1. **Fixed-Point Iteration Method**  
   - Iteratively computes the root using the formula \(x = g(x)\)  
   - Convergence depends on the choice of g(x)

2. **Bisection Method**  
   - Uses interval halving where the function changes sign  
   - Guaranteed convergence for continuous functions

3. **Regula-Falsi Method (False Position)**  
   - Similar to Bisection but uses linear interpolation for faster convergence

4. **Newton-Raphson Method**  
   - Uses derivative of the function  
   - Converges faster but requires differentiable function

5. **Secant Method**  
   - Similar to Newton-Raphson but does not require derivative  
   - Uses previous two points to approximate slope

---

## Example Function

All examples in the notebook use the function:  
\[
f(x) = x^3 - x - 2
\]  

Each method computes the root of f(x) and generates:  
- **Error Table** (Iteration-wise)  
- **Root Plot** on function graph  
- **Error Convergence Plot**

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/vimal-kumar-bhu/root-finding-methods-python.git
