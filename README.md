# david
import math
a = float(input("Ingrese el valor de A: "))
b = float(input("Ingrese el valor de B: "))
c = float(input("Ingrese el valor de C: "))

x = (b**2)-(4*a*c)

if x < 0:
    print("Solucion solo en numeros complejos")
elif x == 0:
    x1 = (-b) / (2*a)
    print("%.2f" % x1)
else:
    x1 = (-b + math.sqrt(x)) / (2*a)
    x2 = (-b - math.sqrt(x)) / (2*a)

    print("X1: ", x1)
    print("X2: ", x2)
