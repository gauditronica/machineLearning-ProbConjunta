#Importa el modulo de aleatorios
from random import randint

# Cantidad de elementos del conjunto X
X = 4

#Cantidad de elementos del conjunto Y
Y = 5

#Elemento con el que se calculará la frecuencia relativa
x = 0

#Elemento con el que se calculará la frecuencia relativa
y = 2

#Cantidad de experimentos
n = 10000000

#Código de error
error = 0

#Variable de conteo de coincidencias
cont = 0

#Verificación de error
if   X <= 0 or Y <= 0 : error = 1 #Error de cantidad de elementos del conjunto
elif x <  0 or x >= X : error = 2 #Error si el elemento no pertenece al conjunto
elif y <  0 or y >= Y : error = 2
elif n <= 0           : error = 3 #Error en la cantidad de experimentos
else:
    for i in range(n):
        if (randint(0,X-1)==x) and (randint(0,Y-1)==y): cont += 1

#Imprime el error
if error != 0: print("Error: ",error)

#frecuencia relativa
print("Probabilidad conjunta de x = ",x,"y y =: ",y," : ",cont/n)
