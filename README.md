# sobreviviendo_a_la_programacion_8



# 1. Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.


```pseudocode
lista=[]   
x:int= int(input("ingresa la cantidad de elementos de la lista: "))
for i in range(x):
    valor=int(input("Ingrese un valor entero:"))
    lista.append(valor)
print(lista)
print("el promedio de este arreglo de lista es:")
print(sum(lista)/x)

```




# 2. Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.


```pseudocode
lista1=[]  
lista2=[] 
x:int= int(input("ingresa la cantidad de elementos de la lista: "))
for i in range(x):
    valorProductopunto=int(input("Ingrese un valor entero perteneciente a la lista 1:"))
    lista1.append(valorProductopunto)

for i in range(x):
    valorProductopunto=int(input("Ingrese un valor entero perteneciente a la lista 2:"))
    lista2.append(valorProductopunto)

def CalcularProductoPunto(lista1, lista2)->int:
    ProductoPunto = 0
    y = 0
    for y in range(x):
       ProductoPunto+= ((lista1[y])*(lista2[y]))
    return ProductoPunto

if __name__ == "__main__":
    ProductoPunto = CalcularProductoPunto (lista1, lista2)

print(lista1)
print(lista2)
print("El producto punto de estos dos arreglos de listas es: ")
print(ProductoPunto)
```



# 3. Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.


```pseudocode
lista1=[]   
lista2=[]
x:int= int(input("ingresa la cantidad de elementos de la lista: "))
for i in range(x):
    valordelalista=int(input("Ingrese un valor entero:"))
    if valordelalista != 0:
        lista1.append(valordelalista)
    else:
        lista2.append(valordelalista)

Lalista = lista1 + lista2

print(f"{Lalista}")
```



# 4. Revisar que son los algoritmos de sorting, entender bubble-sort


 - ¿que son los algoritmos de sorting?

son procedimientos o métodos utilizados para organizar un conjunto de datos de manera sistemática. La tarea principal de un algoritmo de ordenamiento es reorganizar una lista de elementos (como números, palabras o cualquier otro tipo de datos) en un orden específico, generalmente en orden ascendente o descendente.



 - entender bubble-sort

Por lo que entendi, valga la redundacia, es un algoritmo de ordenamiento utilizado para ordenar los elementos de una lista. Va ordenanado los elementos "swapiando" cada uno. Este procedimiento se repite varias veces hasta que la lista este ordenada de menor a mayor.




![image](https://github.com/EmpanadasCONGuaro/sobreviviendo_a_la_programacion_8/assets/142174506/cb84e8a2-2cd8-4534-80af-9e5720eaacef)



# imagen que nanie pidio, pero sirve para entender mejor.




#tengo que decir que este reto casi no me sale. Tuve que buscar varias ayudas incluidas de internet y de personas por que simplemente no entendia,  y si, estaba contra el tiempo :(
# 
