from math import *
def solve_linear(equation,var='x'):
    expression=equation.replace("=","-(")+")"
    grouped=eval(expression.replace(var,'1j'))
    return-grouped.real/grouped.imag
solve_linear("2*x+3=x-6")
