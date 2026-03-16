# Root-Finding Methods in Python

This repository contains Python implementations of common **root-finding methods** used in numerical analysis and scientific computing.  
Each method includes:
- Function implementation
- Error table using pandas
- Function and root plot using matplotlib
- Error convergence plot

---

## Methods Included

1. **Fixed-Point Iteration Method**  
2. **Bisection Method**  
3. **Regula-Falsi Method**  
4. **Newton-Raphson Method**  
5. **Secant Method**  

---

## Example Usage

### Bisection Method
```python
from bisection_method import bisection_method

f = lambda x: x**3 - x - 2
root, errors, iterations = bisection_method(f, 1, 2)
print("Root ≈", root)
