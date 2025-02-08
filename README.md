# funciones-breves-para-el-reto-8

=============================================================

El objetivo era resolver el reto 8, el cual consistia en
realizar algoritmos con funciones .args, lambdas y
recursivas
A continuacion adjunto la imagen del repo del profe Felipe:

============================================================

![image](https://github.com/user-attachments/assets/1e679410-433f-425d-94be-38020cbe719c)

============================================================

 >-Asi que adjuntare capturas mostrando como estan
 >diseñados los codigos para cumplir con cada punto del reto,
 >los realice en visual studio code, a su vez adjuntaré
 >los codigos para que puedan ser copiados y probados.

============================================================

# Punto-1

![image](https://github.com/user-attachments/assets/4433051f-22eb-40f4-8fee-83eab75dcb68)

```

import time

start_time = time.time()
# instrucciones sobre las cuales se quiere medir tiempo de ejecución

if __name__ == "__main__":
  a = int(input("Ingrese numero a: "))
  elevado = (lambda n: 2 ** n)(a)
  print("El resultado de 2 elavado a " + str(a) + " es " + str(elevado))


end_time = time.time()

timer = end_time - start_time
print("el tiempo que demoro el algoritmo en culminar fue de", (timer), "segundos") 

```

============================================================

![image](https://github.com/user-attachments/assets/8f7fc4f5-1e9e-41cd-9691-915df0c6c951)

```

import time

start_time = time.time()

if __name__ == "__main__":
  a = int(input("Ingrese numero: "))
  resultado = lambda n: "Negativo" if n < 0 else ("positivo" if n > 0 else "cero")
  que_es = resultado(a)
  print("El numero " + str(a) + " es " + str(que_es))


end_time = time.time()

timer = end_time - start_time
print("el tiempo que demoro el algoritmo en culminar fue de", (timer), "segundos")

```

============================================================

![image](https://github.com/user-attachments/assets/2f32ea06-7020-4a79-8d90-d97a1656d259)


```

import time

start_time = time.time()

if __name__ == "__main__":
    a = int(input("Ingrese un numero natural"))
    b = float(input("Ingrese un numero natural"))
    function = (lambda n, x: n ** x)(a,b)
    print (" el numero " + str(a) +" elevado a " + str(b) + " es " + str(function))

end_time = time.time()

timer = end_time - start_time
print("el tiempo que demoro el algoritmo en culminar fue de", (timer), "segundos") 

```

============================================================

# Punto-2

![image](https://github.com/user-attachments/assets/91195678-3b5e-46d1-81fc-d3469acb5198)

```

def cuadrados_2(*args) -> None:
    n = args[0]
    for a in range( 1, n + 1):
        print(a ** 2)

if __name__ == "__main__":
    a = int(input("Ingrese numero a: "))
    cuadrado_2 = cuadrados_2(a)

```

============================================================

![image](https://github.com/user-attachments/assets/3c3e0847-7f13-4fa7-9958-ea0c18d8ccfe)

```
def multiplo(*args) -> None:

    if b != 0:
        if a % b == 0:
            print (str(a) + " es multiplo de " + str(b))
        else:
            print (str(a) + " no es multiplo de " + str(b))
    else:
        print (" El segundo número debe ser distinto de 0 " )

if __name__ == "__main__":
    a = float(input("Ingrese el primer numero: "))
    b = float(input("Ingrese el segundo numero: "))
solucion= multiplo(a,b)

```

============================================================

![image](https://github.com/user-attachments/assets/1bfdc980-921e-4eee-964b-f637125b10bd)

```

def par_o_impar(*args) -> None:
    if ord(n) % 2 == 0:
        print ( "Su caracter", n,"en codigo ASCII es par" )
    else:
        print ( "Su caracter", n,"en codigo ASCII es impar" )

if __name__ == "__main__":
    n = (input("Digite una letra o un caracter cualquiera a excepcion de un número "))
    ord(n)
    resultado = par_o_impar(n)

```

============================================================

# Punto-3

![image](https://github.com/user-attachments/assets/4534093c-b489-4e2f-8eec-7d468e291534)

```

import time

start_time = time.time()
def potencia_recursiva(n: float, x: float)-> int:
    if  x == 0:
        return 1
    elif x == 1:
        return n
    elif x < 0:
        return 1/potencia_recursiva(n, -x)
    else:
        return n *potencia_recursiva(n, x-1)
if __name__ == "__main__":
    n = float(input("Ingrese un numero "))
    x = float(input("Ingrese un exponente"))
    resultado = potencia_recursiva(n, x)
    print (" el numero " + str(n) +" elevado a " + str(x) + " es " + str(resultado))

end_time = time.time()

timer = end_time - start_time
print("el tiempo que demoro el algoritmo en culminar fue de", (timer), "segundos") 

```

============================================================

# Punto-5

![image](https://github.com/user-attachments/assets/c8d210f5-322e-406e-ae16-04b0cd1252f3)

============================================================

# Punto-6

https://www.linkedin.com/in/nicolas-ramirez-rodriguez-002aa2347/ 

============================================================

