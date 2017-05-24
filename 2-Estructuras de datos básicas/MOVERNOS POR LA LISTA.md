## MOVERNOS POR UNA LISTA

Para movernos por la lista y acceder a uno de sus elementos utilizamos el nombre con el que hacemos referencia a la lista. En este caso lo hemos llamado lista, aunque podría haber sido cualquier otro nombre válido. Para referirnos a un elemento de la lista utilizamos los corchetes indicando un índice. Dicho índice va de 0 hastra n-1, siendo n el número de elementos que tiene la lista.

Vamos a ver un ejemplo:

Tenemos la lista anterior
```python
lista = ["hola",69,"curso",[1,2,3,4,5]] print(lista[0]) 

hola 

print(lista[3])

[1, 2, 3, 4, 5]
 

Si queremos acceder al 2 dentro de la lista [1,2,3,4,5] es tan simple como:

print(lista[3][1]) 

2
```
Como vimos con el operador [ ] podemos hacer referencia a cualquier elemento de la lista de 0 a n-1 pero Python trae consigo algo que es recorrer la lista de último al primero utilizando números negativos veamos un ejemplo:
```python
nombres = ["Pablo","Manu","José Alonso","Renato"]

print(nombres[-1])

Renato

print(nombres[-4])

Pablo
```
Como siempre nos gusta poner a prueba el lenguaje; qué nos pasa si ponemos print(nombres[-5]) o print (nombres[4]). Nos genera un error que índice, lista fuera de rango así:
```python
Traceback (most recent call last):
  File "nombres.py", line 26, in <module>
    print(nombres[-5])
IndexError: list index out of range 


Traceback (most recent call last):
  File "otr_input.py", line 26, in <module>
    print(nombres[4])
IndexError: list index out of range
```
