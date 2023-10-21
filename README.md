# Reto_9_xddddd

## Punto 1 

De los retos anteriores selecione 3 funciones y escribalas en forma de lambdas.


# Ejercicio 3 reto 6

```
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


# Ejercicio 1 Reto 6

```

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

## Ejercicio 5 reto 6 

```
Ejercicio interes compuesto con Lambda

if __name__ == "__main__":
  
  prestamo_inicial = float(input("Ingrese Préstamo inicial: "))
  tasa_interes = float(input("Ingrese la tasa de interes: "))
  tiempo = float(input("Ingrese tiempo en meses: "))
  valor_final = lambda prestamo_inicial, tasa_interes, tiempo: prestamo_inicial * ((1 + tasa_interes / 100) ** tiempo)
  valor_prestamo = valor_final(prestamo_inicial, tasa_interes, tiempo)
  print("El valor final del préstamo es: " + str(valor_prestamo))

```

## Punto 2

De los retos anteriores selecione 3 funciones y escribalas con argumentos no definidos (*args).

```
Ejercicio 4 Reto 6

def vuelto (*args) = float:
  valor_vueltas=((B)-((P*300)+(M*3300)+(H*350))) 
  return valorvueltas

if __name__ == "__main__":
 B= float(input("ingrese el valor del billete:"))
 P= float(input("ingrese el numero de panes:"))
 M= float(input("ingrese el numero de bolsas de leche:"))
 H= float = float(input("ingrese el numero de huevos:"))
 valorvueltas=vuelto(P,M,H,B)



 P=float(input("Cuantos panes compaste: "))
    print("Te queda en: " + str(300*P))

    M=float(input("Cuantas bolsas de leche compraste: "))
    print("Te queda en: " + str(3300*M))

    H= float (input("Cuanto huevos compraste: "))
    print("Te queda en: " + str(350*H))

print("Te quedan de vueltas un total de: " + str(vuelto))

```

# Ejercicio 6 Reto 6 
Ejercicio de Covid

```

def no_contagiados(c:int,d:int)->int:
contagios= c*(2*d)
contagios_actuales = args[0]
 dias_transcurridos = args[1]




if __name__ == "__main__":

    c=int(input("Numero de contagios: "))
    d=int(input("Dias transcurridos: "))

contagios_total= no_contagiados(c,d)

print("El numero de contagiados pasado dichos dias es: " + str(no_contagiados))

```
# Ejercicio 



## Punto 3

Escriba una función recursiva para calcular la operación de la potencia.

```
def potencia(base, exponente):
    if exponente == 0:
     return 1
    elif exponente < 0:
     return 1 / (base * potencia(base, -exponente * 1))
    else:
     return base * potencia(base, exponente - 1)

```

## Punto 5

Crear cuenta en stackoverflow y adjuntar imagen en el repo

## AQUI TAAAAAA :333

[![Captura.png](https://i.postimg.cc/1RVGLzPc/Captura.png)](https://postimg.cc/Z0ZvN4WC)

## Punto 6 

Cosas de adultos....ir a linkedin y crear perfil....NO IMPORTA que estén iniciando, si tienen tiempo para redes poco útiles como fb, insta, o tiktok tienen tiempo para crear un perfil mamalón. Dejar enlace en el repo.

AQUI TAAAA: https://www.linkedin.com/in/juan-andres-valderrama-parra-833310297/

