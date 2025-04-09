# integral-calculator
import sympy as sp

def calculate_integral(expression, variable):
    """Calculate the indefinite integral of a given expression."""
    x = sp.Symbol(variable)
    integral = sp.integrate(expression, x)
    return integral

# Example usage
if __name__ == "__main__":
    expr = "x**2 + 3*x + 5"
    variable = "x"
    result = calculate_integral(expr, variable)
    print(f"Integral of {expr} with respect to {variable}: {result}")
was
