# Reto_9_xddddd

## Punto 1 

De los retos anteriores selecione 3 funciones y escribalas en forma de lambdas.

```
# Ejercicio 3 reto 6

Ejercicio para calcular carne sin lambda:


import math 

def Calcular_cantidad_de_carne(N:float, M:float, K:float)-> float:
    Cantidad_carne= (6*N) + (7*M) + (1*K)
    return Cantidad_carne

if __name__ == "__main__":

    N=float(input("Ingresa el número de Gallinas: "))
    M=float(input("Ingresa el número de Gallos: "))
    K=float(input("Ingresa el número de Pollitos: "))

    Carne_en_total= Calcular_cantidad_de_carne (N,M,K)
    print("La cantidad total de carne es: " + str(Carne_en_total))


Con lambda:


import math 

def Calcular_cantidad_de_carne(N:float, M:float, K:float)-> float:
    Cantidad_carne= (6*N) + (7*M) + (1*K)
    return Cantidad_carne

if __name__ == "__main__":

cantidad_carne_total = lambda N, M, K: (6*N) + (7*M) + (1*K)
Final= cantidad_carne_total(N, M ,K)

```

```
# Ejercicio 1 Reto 6

Calcular volumen superficial Sin lambda

import math 
pi=math.pi

def CalcularVolumen(r1:float,r2:float,h:float)-> float:
    Vol= ((4*(pi*r1**3))/3) + ((pi*r2**2*h)/3)
    return Vol

def CalcularAreaSuperficial(r1:float,r2:float,h:float)-> float:
    Asup= (4*pi*r1**2) + (pi*r2*(math.sqrt((r2**2)+(h**2))))
    return Asup

if __name__ == "__main__":
    r1=float(input("Ingresa el primer radio de la esfera: "))
    r2=float(input("Ingresa ahora el radio del cono: "))
    h=float(input("Ingresa una altura del cono: "))
    volumentotal= CalcularVolumen(r1,r2,h)
    Superficietotal= CalcularAreaSuperficial (r1,r2,h)
print("El volumen total es: "+str(volumentotal))
print("El área superficial total es: "+ str(Superficietotal))


Con lambda:

import math 
pi=math.pi

def CalcularVolumen as CV(r1:float,r2:float,h:float)-> float:
    Vol= ((4*(pi*r1**3))/3) + ((pi*r2**2*h)/3)
    return Vol

def CalcularAreaSuperficial as AS(r1:float,r2:float,h:float)-> float:
    Asup= (4*pi*r1**2) + (pi*r2*(math.sqrt((r2**2)+(h**2))))
    return Asup

vol_total= lambda (Vol,((4*(pi*r1**3))/3) + ((pi*r2**2*h)/3), Asup,(4*pi*r1**2) + (pi*r2*(math.sqrt((r2**2)+(h**2)))) )
Final= area_total(Vol,asup)

if __name__ == "__main__":
    r1=float(input("Ingresa el primer radio de la esfera: "))
    r2=float(input("Ingresa ahora el radio del cono: "))
    h=float(input("Ingresa una altura del cono: "))
    
print("El volumen total es: "+str(volumentotal))
print("El área superficial total es: "+ str(Superficietotal))

```


