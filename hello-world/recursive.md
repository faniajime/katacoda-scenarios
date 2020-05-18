## Recursividad

Las funciones recursivas se llaman a sí mismas para resolver un problema.

La funcion factorial se crea de la multiplicacion de todos los numeros previos.

![image.png](attachment:image.png)


`
def factorial(n):
    if n == 1: #condicion de parada
        return n
    else: 
        return n*factorial(n-1)
    
factorial(3)
`{{execute}}
