# PyCalcEngine

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/PyCalcEngine.git
```

2. Install required packages:
```bash
pip install numpy matplotlib
```

3. Open ```PyCalcEngine.ipynb``` in **Jupyter Notebook**

### License

1. Import the functions in a notebook:
```python
from PyCalcEngine import derivative, integral, plot_function
```

2. Define a function and use the engine:
```python
# Plot function, derivative, and integral
plot_function(np.sin, 0, 2*np.pi)

# Compute integral
result = integral(lambda x: x**2, 0, 1)
print(result)
```

3. Experiment with different families of functions:

```python
f_poly = lambda x: x**3 + 2*x**2 - x # polynomial
print("Integral of f_poly from 0 to 2:", integral(f_poly, 0, 2))
plot_function(f_poly, -5, 5)

f_sin = np.sin # trigonometric
print("Integral of sin(x) from 0 to pi:", integral(f_sin, 0, np.pi))
plot_function(f_sin, 0, 2*np.pi)

f_exp = np.exp # exponential
print("Integral of exp(x) from 0 to 1:", integral(f_exp, 0, 1))
plot_function(f_exp, 0, 3)
```

### Usage
```This project is open-source and free to use. Feel free to fork, experiment, and improve!```
