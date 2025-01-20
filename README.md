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

![image](https://github.com/user-attachments/assets/c8d210f5-322e-406e-ae16-04b0cd1252f3)

============================================================

https://www.linkedin.com/in/nicolas-ramirez-rodriguez-002aa2347/ 

============================================================

