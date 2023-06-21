100 ejercicios de arreglos (arrays) con Python para practicar!

1. Crea un arreglo vacío.
```python
arreglo = []
print(arreglo)
```
Resultado: `[]`

2. Crea un arreglo con 5 elementos enteros.
```python
arreglo = [1, 2, 3, 4, 5]
print(arreglo)
```
Resultado: `[1, 2, 3, 4, 5]`

3. Accede al primer elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
primer_elemento = arreglo[0]
print(primer_elemento)
```
Resultado: `1`

4. Accede al último elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
ultimo_elemento = arreglo[-1]
print(ultimo_elemento)
```
Resultado: `5`

5. Accede al tercer elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
tercer_elemento = arreglo[2]
print(tercer_elemento)
```
Resultado: `3`

6. Cambia el segundo elemento del arreglo por otro valor.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo[1] = 10
print(arreglo)
```
Resultado: `[1, 10, 3, 4, 5]`

7. Imprime todos los elementos del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
for elemento in arreglo:
    print(elemento)
```
Resultado:
```
1
2
3
4
5
```

8. Imprime los elementos del arreglo en orden inverso.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo_inverso = arreglo[::-1]
print(arreglo_inverso)
```
Resultado: `[5, 4, 3, 2, 1]`

9. Calcula la longitud del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
longitud = len(arreglo)
print(longitud)
```
Resultado: `5`

10. Suma todos los elementos del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
suma = sum(arreglo)
print(suma)
```
Resultado: `15`
Aquí tienes los ejercicios del 11 al 100 resueltos:

11. Encuentra el valor máximo en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
maximo = max(arreglo)
print(maximo)
```
Resultado: `5`

12. Encuentra el valor mínimo en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
minimo = min(arreglo)
print(minimo)
```
Resultado: `1`

13. Ordena los elementos del arreglo de forma ascendente.
```python
arreglo = [5, 3, 1, 4, 2]
arreglo.sort()
print(arreglo)
```
Resultado: `[1, 2, 3, 4, 5]`

14. Ordena los elementos del arreglo de forma descendente.
```python
arreglo = [5, 3, 1, 4, 2]
arreglo.sort(reverse=True)
print(arreglo)
```
Resultado: `[5, 4, 3, 2, 1]`

15. Crea un arreglo de 10 elementos iguales a 5.
```python
arreglo = [5] * 10
print(arreglo)
```
Resultado: `[5, 5, 5, 5, 5, 5, 5, 5, 5, 5]`

16. Crea un arreglo de números pares del 1 al 10.
```python
arreglo = list(range(2, 11, 2))
print(arreglo)
```
Resultado: `[2, 4, 6, 8, 10]`

17. Crea un arreglo de números impares del 1 al 10.
```python
arreglo = list(range(1, 10, 2))
print(arreglo)
```
Resultado: `[1, 3, 5, 7, 9]`

18. Crea un arreglo de letras del alfabeto.
```python
import string

letras = list(string.ascii_lowercase)
print(letras)
```
Resultado: `['a', 'b', 'c', ..., 'x', 'y', 'z']`

19. Crea un arreglo de cadenas de texto.
```python
arreglo = ['Hola', 'Mundo', 'Python']
print(arreglo)
```
Resultado: `['Hola', 'Mundo', 'Python']`

20. Concatena dos arreglos.
```python
arreglo1 = [1, 2, 3]
arreglo2 = [4, 5, 6]
concatenado = arreglo1 + arreglo2
print(concatenado)
```
Resultado: `[1, 2, 3, 4, 5, 6]`

21. Copia un arreglo en otro.
```python
arreglo1 = [1, 2, 3]
arreglo2 = arreglo1.copy()
print(arreglo2)
```
Resultado: `[1, 2, 3]`

22. Encuentra si un valor dado está en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
esta_en_arreglo = valor in arreglo
print(esta_en_arreglo)
```
Resultado: `True`

23. Cuenta cuántas veces aparece un valor en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3

, 2]
valor = 2
contador = arreglo.count(valor)
print(contador)
```
Resultado: `3`

24. Elimina un elemento específico del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
arreglo.remove(valor)
print(arreglo)
```
Resultado: `[1, 2, 4, 5]`

25. Elimina el primer elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.pop(0)
print(arreglo)
```
Resultado: `[2, 3, 4, 5]`

26. Elimina el último elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.pop()
print(arreglo)
```
Resultado: `[1, 2, 3, 4]`

27. Elimina todos los elementos del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.clear()
print(arreglo)
```
Resultado: `[]`

28. Inserta un elemento en una posición específica del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 10
posicion = 2
arreglo.insert(posicion, valor)
print(arreglo)
```
Resultado: `[1, 2, 10, 3, 4, 5]`

29. Divide el arreglo en dos partes.
```python
arreglo = [1, 2, 3, 4, 5]
mitad = len(arreglo) // 2
parte1 = arreglo[:mitad]
parte2 = arreglo[mitad:]
print(parte1)
print(parte2)
```
Resultado:
```
[1, 2]
[3, 4, 5]
```

30. Combina dos arreglos en uno solo.
```python
arreglo1 = [1, 2, 3]
arreglo2 = [4, 5, 6]
combinado = arreglo1 + arreglo2
print(combinado)
```
Resultado: `[1, 2, 3, 4, 5, 6]`

31. Invierte el orden de los elementos del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.reverse()
print(arreglo)
```
Resultado: `[5, 4, 3, 2, 1]`

32. Crea una copia invertida del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
copia_invertida = arreglo[::-1]
print(copia_invertida)
```
Resultado: `[5, 4, 3, 2, 1]`

33. Cuenta cuántos elementos pares hay en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
pares = sum(1 for num in arreglo if num % 2 == 0)
print(pares)
```
Resultado: `2`

34. Cuenta cuántos elementos impares hay en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
impares = sum(1 for num in arreglo if num % 2 != 0)
print(impares)
```
Resultado: `3`

35. Encuentra el índice de la primera aparición de un valor en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
valor = 2
indice = arreglo.index(valor)
print(indice)
```
Resultado: `1`

36. Encuentra el índice de la última aparición de un valor en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
valor = 2
indice = len(arreglo) - arreglo[::-1].index(valor) - 1
print(indice)
```
Resultado: `7`

37. Encuentra todos los índices donde aparece un valor en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
valor = 2
indices = [i for i, num in enumerate(arreglo) if num == valor]
print(indices)
```
Resultado: `[1, 5, 7]`

38. Calcula la suma de todos los elementos pares del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
suma_pares = sum(num for num in arreglo if num % 2 == 0)
print(suma_pares)
```
Resultado: `6`

39. Calcula la suma de todos los elementos impares del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
suma_impares = sum(num for num in arreglo if num % 2 != 0)
print(suma_impares)
```
Resultado: `9`

40. Calcula la media de los elementos del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
media = sum(arreglo) / len(arreglo)
print(media)
```
Resultado: `3.0`

41. Calcula la mediana de los elementos del arreglo.
```python
import statistics

arreglo = [1, 2, 3, 4, 5]
mediana = statistics

.median(arreglo)
print(mediana)
```
Resultado: `3`

42. Calcula la desviación estándar de los elementos del arreglo.
```python
import statistics

arreglo = [1, 2, 3, 4, 5]
desviacion_estandar = statistics.stdev(arreglo)
print(desviacion_estandar)
```
Resultado: `1.5811388300841898`

43. Calcula la varianza de los elementos del arreglo.
```python
import statistics

arreglo = [1, 2, 3, 4, 5]
varianza = statistics.variance(arreglo)
print(varianza)
```
Resultado: `2.5`

44. Elimina los elementos duplicados del arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
arreglo_sin_duplicados = list(set(arreglo))
print(arreglo_sin_duplicados)
```
Resultado: `[1, 2, 3, 4, 5]`

45. Crea un nuevo arreglo que contenga solo los elementos únicos del arreglo original.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
arreglo_unico = [num for num in arreglo if arreglo.count(num) == 1]
print(arreglo_unico)
```
Resultado: `[1, 4, 5]`

46. Une todos los elementos del arreglo en una sola cadena de texto.
```python
arreglo = ['Hola', 'Mundo', 'Python']
cadena = ''.join(arreglo)
print(cadena)
```
Resultado: `'HolaMundoPython'`

47. Une todos los elementos del arreglo separados por un espacio.
```python
arreglo = ['Hola', 'Mundo', 'Python']
cadena = ' '.join(arreglo)
print(cadena)
```
Resultado: `'Hola Mundo Python'`

48. Convierte todos los elementos del arreglo a mayúsculas.
```python
arreglo = ['Hola', 'Mundo', 'Python']
arreglo_mayusculas = [elem.upper() for elem in arreglo]
print(arreglo_mayusculas)
```
Resultado: `['HOLA', 'MUNDO', 'PYTHON']`

49. Convierte todos los elementos del arreglo a minúsculas.
```python
arreglo = ['Hola', 'Mundo', 'Python']
arreglo_minusculas = [elem.lower() for elem in arreglo]
print(arreglo_minusculas)
```
Resultado: `['hola', 'mundo', 'python']`

50. Verifica si todos los elementos del arreglo cumplen una condición.
```python
arreglo = [1, 2, 3, 4, 5]
todos_cumplen_condicion = all(num > 0 for num in arreglo)
print(todos_cumplen_condicion)
```
Resultado: `True`

51. Verifica si al menos un elemento del arreglo cumple una condición.
```python
arreglo = [1, 2, 3, 4, 5]
alguno_cumple_condicion = any(num % 2 == 0 for num in arreglo)
print(alguno_cumple_condicion)
```
Resultado: `True`

52. Cuenta cuántos elementos del arreglo son mayores que un valor dado.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
mayores = sum

(1 for num in arreglo if num > valor)
print(mayores)
```
Resultado: `2`

53. Cuenta cuántos elementos del arreglo son menores que un valor dado.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
menores = sum(1 for num in arreglo if num < valor)
print(menores)
```
Resultado: `2`

54. Encuentra el primer elemento mayor que un valor dado en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
mayor = next((num for num in arreglo if num > valor), None)
print(mayor)
```
Resultado: `4`

55. Encuentra el primer elemento menor que un valor dado en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
menor = next((num for num in arreglo if num < valor), None)
print(menor)
```
Resultado: `2`

56. Cuenta cuántos elementos distintos hay en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
elementos_distintos = len(set(arreglo))
print(elementos_distintos)
```
Resultado: `5`

57. Calcula la suma acumulada de los elementos del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
suma_acumulada = [sum(arreglo[:i+1]) for i in range(len(arreglo))]
print(suma_acumulada)
```
Resultado: `[1, 3, 6, 10, 15]`

58. Crea un nuevo arreglo que contenga los elementos pares del arreglo original.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo_pares = [num for num in arreglo if num % 2 == 0]
print(arreglo_pares)
```
Resultado: `[2, 4]`

59. Crea un nuevo arreglo que contenga los elementos impares del arreglo original.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo_impares = [num for num in arreglo if num % 2 != 0]
print(arreglo_impares)
```
Resultado: `[1, 3, 5]`

60. Calcula la suma de los elementos en posiciones pares del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
suma_posiciones_pares = sum(arreglo[i] for i in range(len(arreglo)) if i % 2 == 0)
print(suma_posiciones_pares)
```
Resultado: `9`

61. Calcula la suma de los elementos en posiciones impares del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
suma_posiciones_impares = sum(arreglo[i] for i in range(len(arreglo)) if i % 2 != 0)
print(suma_posiciones_impares)
```
Resultado: `6`

62. Encuentra el elemento más frecuente en el arreglo.
```python
from collections import Counter

arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
frecuencias = Counter(ar

reglo)
elemento_frecuente = frecuencias.most_common(1)[0][0]
print(elemento_frecuente)
```
Resultado: `2`

63. Encuentra el elemento menos frecuente en el arreglo.
```python
from collections import Counter

arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
frecuencias = Counter(arreglo)
elemento_menos_frecuente = frecuencias.most_common()[-1][0]
print(elemento_menos_frecuente)
```
Resultado: `1`

64. Crea un nuevo arreglo que contenga solo los elementos que se repiten en el arreglo original.
```python
from collections import Counter

arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
frecuencias = Counter(arreglo)
elementos_repetidos = [elem for elem, count in frecuencias.items() if count > 1]
print(elementos_repetidos)
```
Resultado: `[2, 3]`

65. Crea un nuevo arreglo que contenga solo los elementos que no se repiten en el arreglo original.
```python
from collections import Counter

arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
frecuencias = Counter(arreglo)
elementos_no_repetidos = [elem for elem, count in frecuencias.items() if count == 1]
print(elementos_no_repetidos)
```
Resultado: `[1, 4, 5]`

66. Cuenta cuántas veces se repite cada elemento en el arreglo.
```python
from collections import Counter

arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
frecuencias = Counter(arreglo)
print(frecuencias)
```
Resultado: `Counter({2: 3, 3: 2, 1: 1, 4: 1, 5: 1})`

67. Ordena el arreglo de forma ascendente.
```python
arreglo = [3, 1, 4, 2, 5]
arreglo.sort()
print(arreglo)
```
Resultado: `[1, 2, 3, 4, 5]`

68. Ordena el arreglo de forma descendente.
```python
arreglo = [3, 1, 4, 2, 5]
arreglo.sort(reverse=True)
print(arreglo)
```
Resultado: `[5, 4, 3, 2, 1]`

69. Crea un nuevo arreglo que contenga los elementos del arreglo original en orden inverso sin modificar el arreglo original.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo_inverso = arreglo[::-1]
print(arreglo_inverso)
```
Resultado: `[5, 4, 3, 2, 1]`

70. Crea un nuevo arreglo que contenga los elementos del arreglo original en orden aleatorio.
```python
import random

arreglo = [1, 2, 3, 4, 5]
arreglo_aleatorio = random.sample(arreglo, len(arreglo))
print(arreglo_aleatorio)
```
Resultado: `[3, 2, 1, 5, 4]`

71. Crea un nuevo arreglo que contenga los elementos del arreglo original en orden

 inverso aleatorio.
```python
import random

arreglo = [1, 2, 3, 4, 5]
arreglo_inverso_aleatorio = random.sample(arreglo, len(arreglo))[::-1]
print(arreglo_inverso_aleatorio)
```
Resultado: `[4, 5, 3, 2, 1]`

72. Calcula el producto de todos los elementos del arreglo.
```python
import numpy as np

arreglo = [1, 2, 3, 4, 5]
producto = np.prod(arreglo)
print(producto)
```
Resultado: `120`

73. Calcula la potencia de cada elemento del arreglo elevado a un valor dado.
```python
arreglo = [1, 2, 3, 4, 5]
exponente = 2
potencias = [num ** exponente for num in arreglo]
print(potencias)
```
Resultado: `[1, 4, 9, 16, 25]`

74. Calcula el factorial de cada elemento del arreglo.
```python
import math

arreglo = [1, 2, 3, 4, 5]
factoriales = [math.factorial(num) for num in arreglo]
print(factoriales)
```
Resultado: `[1, 2, 6, 24, 120]`

75. Verifica si el arreglo está ordenado de forma ascendente.
```python
arreglo = [1, 2, 3, 4, 5]
esta_ordenado_ascendente = all(arreglo[i] <= arreglo[i+1] for i in range(len(arreglo)-1))
print(esta_ordenado_ascendente)
```
Resultado: `True`

76. Verifica si el arreglo está ordenado de forma descendente.
```python
arreglo = [5, 4, 3, 2, 1]
esta_ordenado_descendente = all(arreglo[i] >= arreglo[i+1] for i in range(len(arreglo)-1))
print(esta_ordenado_descendente)
```
Resultado: `True`

77. Crea un nuevo arreglo que contenga los elementos del arreglo original en orden ascendente sin modificar el arreglo original.
```python
arreglo = [3, 1, 4, 2, 5]
arreglo_ordenado_ascendente = sorted(arreglo)
print(arreglo_ordenado_ascendente)
```
Resultado: `[1, 2, 3, 4, 5]`

78. Crea un nuevo arreglo que contenga los elementos del arreglo original en orden descendente sin modificar el arreglo original.
```python
arreglo = [3, 1, 4, 2, 5]
arreglo_ordenado_descendente = sorted(arreglo, reverse=True)
print(arreglo_ordenado_descendente)
```
Resultado: `[5, 4, 3, 2, 1]`

79. Cuenta cuántas veces aparece un elemento específico en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
elemento = 2
apariciones = arreglo.count(elemento)
print(apariciones)
```
Resultado: `3`

80. Verifica si el arreglo está vacío.
```python
arreglo = []
esta_vacio = len(arreglo) == 0
print(esta_vacio)
```
Resultado: `True`

81. Verifica si el arreglo contiene al

 menos un elemento.
```python
arreglo = []
tiene_elementos = len(arreglo) > 0
print(tiene_elementos)
```
Resultado: `False`

82. Concatena dos arreglos en uno nuevo.
```python
arreglo1 = [1, 2, 3]
arreglo2 = [4, 5, 6]
arreglo_concatenado = arreglo1 + arreglo2
print(arreglo_concatenado)
```
Resultado: `[1, 2, 3, 4, 5, 6]`

83. Convierte el arreglo en una cadena de texto separada por comas.
```python
arreglo = ['Hola', 'Mundo', 'Python']
cadena = ','.join(arreglo)
print(cadena)
```
Resultado: `'Hola,Mundo,Python'`

84. Convierte el arreglo en una cadena de texto separada por un espacio.
```python
arreglo = ['Hola', 'Mundo', 'Python']
cadena = ' '.join(arreglo)
print(cadena)
```
Resultado: `'Hola Mundo Python'`

85. Invierte el orden de los elementos en el arreglo (modifica el arreglo original).
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.reverse()
print(arreglo)
```
Resultado: `[5, 4, 3, 2, 1]`

86. Elimina el primer elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.pop(0)
print(arreglo)
```
Resultado: `[2, 3, 4, 5]`

87. Elimina el último elemento del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo.pop()
print(arreglo)
```
Resultado: `[1, 2, 3, 4]`

88. Elimina un elemento específico del arreglo por su valor.
```python
arreglo = [1, 2, 3, 4, 5]
valor = 3
arreglo.remove(valor)
print(arreglo)
```
Resultado: `[1, 2, 4, 5]`

89. Inserta un elemento en una posición específica del arreglo.
```python
arreglo = [1, 2, 3, 4, 5]
elemento = 10
posicion = 2
arreglo.insert(posicion, elemento)
print(arreglo)
```
Resultado: `[1, 2, 10, 3, 4, 5]`

90. Reemplaza un elemento específico del arreglo por otro valor.
```python
arreglo = [1, 2, 3, 4, 5]
nuevo_valor = 10
posicion = 2
arreglo[posicion] = nuevo_valor
print(arreglo)
```
Resultado: `[1, 2, 10, 4, 5]`

91. Encuentra la posición de la primera aparición de un elemento en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
elemento = 2
posicion = arreglo.index(elemento)
print(posicion)
```
Resultado: `1`

92. Encuentra la posición de la última aparición de un elemento en el arreglo.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
elemento = 2
posicion = len(arreglo) - arreglo[::-1].index(elemento) - 1
print(posicion)
```
Resultado: `7`

93. Verifica si todos los elementos del arreglo son iguales.
```python
arreglo = [1, 1, 1, 1, 1]
son_iguales = all(elem == arreglo[0] for elem in arreglo)
print(son_iguales)
```
Resultado: `True`

94. Verifica si al menos un elemento del arreglo cumple con una condición.
```python
arreglo = [1, 2, 3, 4, 5]
cumple_condicion = any(elem > 3 for elem in arreglo)
print(cumple_condicion)
```
Resultado: `True`

95. Verifica si todos los elementos del arreglo cumplen con una condición.
```python
arreglo = [1, 2, 3, 4, 5]
cumplen_condicion = all(elem > 0 for elem in arreglo)
print(cumplen_condicion)
```
Resultado: `True`

96. Verifica si un elemento específico está presente en el arreglo.
```python
arreglo = [1, 2, 3, 4, 

5]
elemento = 3
esta_presente = elemento in arreglo
print(esta_presente)
```
Resultado: `True`

97. Crea un nuevo arreglo que contenga solo los elementos únicos del arreglo original.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
arreglo_unico = list(set(arreglo))
print(arreglo_unico)
```
Resultado: `[1, 2, 3, 4, 5]`

98. Crea un nuevo arreglo que contenga los elementos del arreglo original en orden inverso sin modificar el arreglo original.
```python
arreglo = [1, 2, 3, 4, 5]
arreglo_inverso = arreglo[::-1]
print(arreglo_inverso)
```
Resultado: `[5, 4, 3, 2, 1]`

99. Crea un nuevo arreglo que contenga los elementos del arreglo original sin los duplicados.
```python
arreglo = [1, 2, 3, 4, 5, 2, 3, 2]
arreglo_sin_duplicados = []
for elem in arreglo:
    if elem not in arreglo_sin_duplicados:
        arreglo_sin_duplicados.append(elem)
print(arreglo_sin_duplicados)
```
Resultado: `[1, 2, 3, 4, 5]`

100. Crea una copia del arreglo original.
```python
import copy

arreglo = [1, 2, 3, 4, 5]
copia_arreglo = copy.deepcopy(arreglo)
print(copia_arreglo)
```
Resultado: `[1, 2, 3, 4, 5]`

