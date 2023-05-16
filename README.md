# Este es el reto 10
#  Y sus punto a continuacion...
## 1. Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.

<details><summary>el codigo esta aqui</summary><p>

``` python
# Se crea la lista con la informacion que nos proporcione el usuario.
def lis1(tam):
    
    lista=[]
    i = int
    # Primero, pedimos el tamaño que va a tener la lista.
    tam =int(input("Digite el tamaño de su lista :"))
    
    for i in range(tam): 
        # Ahora, le pedimos que ingrese cada dato de la lista.
        nun=float(input("Ingrese el elemento "+ str(i) +" : ")) 
        lista.append(nun) 
        
    # Entonces retornamos la lista ya hecha.
    return lista

# llamamos a la funcion que nos creo la lista.
lista=lis1(tam)

# definimos el tamaño de la lista y la variable para hacer la suma de los datos.
tam_lis=len(lista)
sumatoria = 0  

# Hacemos un ciclo para hallar el promedio de la lista. 
for i in lista: 
    sumatoria = sumatoria + i 
    prom_list = sumatoria / tam_lis

# Por ultimo imprimimos el mensaje al usuario con el resultado.
print("El promedio de la lista : "+ str(lista) +"\nes : "+str(prom_list))
```
</p></details></br>

## 2. Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.

<details><summary>el codigo esta aqui</summary><p>

``` python
def lis1(tam):
    
    lista1=[]
    i1 = int
    # Primero, pedimos el tamaño que va a tener la lista 1.
    tam1 =int(input("Digite el tamaño de su lista 1 :"))
    
    for i1 in range(tam1): 
        # Ahora, le pedimos que ingrese cada dato de la lista 1.
        nun1=float(input("Ingrese el elemento "+ str(i1) +" : ")) 
        lista1.append(nun1) 
        
    # Entonces retornamos la lista 1 ya hecha.
    return lista1

def lis2(tam):
    
    lista2=[]
    i2 = int
    # Primero, pedimos el tamaño que va a tener la lista 2.
    tam2 =int(input("Digite el tamaño de su lista 2 :"))
    
    for i2 in range(tam2): 
        # Ahora, le pedimos que ingrese cada dato de la lista 2.
        nun2=float(input("Ingrese el elemento "+ str(i2) +" : ")) 
        lista2.append(nun2) 
        
    # Entonces retornamos la lista 2, ya hecha.
    return lista2

def pro_punto(lis1,lis2)
    lista3 = []
    i3 = int
    num3 = 1
    # creamos la lista a partir de la lista 1  y la lista 2
    for i3 in range(tam2):
        num3=lista1[i3]*lista2[i3]
        lista3.append(num3)
        #ahora sumamos cada dato
    for i3 in lista3 :
        punto=i3+punto
        
    return punto
if __name__ == "__main__":
    lista1=lis1(tam1)
    lista2=lis2(tam2)
    if len(lista1)=len(lista2):
        punto=pro_punto(lis1,lis2)
        print(punto)
    elif :
        print("las lista no son de igual tamaño, por lo tanto no se puede realizar el producto punto. ")


```
</p></details></br>
Por ultimo el punto numero 3.
## 3. Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.

<details><summary>el codigo esta aqui</summary><p>

``` python
def lis1(tam):
    
    lista1=[]
    i1 = int
    # Primero, pedimos el tamaño que va a tener la lista 1.
    tam1 =int(input("Digite el tamaño de su lista 1 :"))
    
    for i1 in range(tam1): 
        # Ahora, le pedimos que ingrese cada dato de la lista 1.
        nun1=float(input("Ingrese el elemento "+ str(i1) +" : ")) 
        lista1.append(nun1) 
    
    print("su lista es :"+str(lista1))
    #acomodamos los 0 al final de la lista
    for i in lista1: 
        if i == 0:
            lista1.remove(i) 
            lista1.append(i)    
    print("su lista modificada es :")
    # Entonces retornamos la lista  ya hecha.
    return lista1
lista=lis1(tam)
print(lista)

```
</p></details></br>

#Esto es  todo lo que tengo :(  . 
