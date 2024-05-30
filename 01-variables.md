# Ejercicios de Python para aprender a trabajar con Estructuras de datos complejos
[Volver a la página del temario](https://github.com/maca-chan/python-ejercicios/tree/main)

**Ejercicio 1:**
- **Ejercicio:** Crea una lista con los números del 1 al 10. Imprime la lista.
- **Solución:**
  ```python
  numeros = list(range(1, 11))
  print(numeros)
  ```

**Ejercicio 2:**
- **Ejercicio:** Dada una lista de nombres `["Ana", "Luis", "Carlos", "María"]`, agrega el nombre "Jorge" al final de la lista. Imprime la lista actualizada.
- **Solución:**
  ```python
  nombres = ["Ana", "Luis", "Carlos", "María"]
  nombres.append("Jorge")
  print(nombres)
  ```

**Ejercicio 3:**
- **Ejercicio:** Crea un diccionario con las capitales de tres países (por ejemplo, España, Francia, Italia). Imprime el diccionario.
- **Solución:**
  ```python
  capitales = {
      "España": "Madrid",
      "Francia": "París",
      "Italia": "Roma"
  }
  print(capitales)
  ```

**Ejercicio 4:**
- **Ejercicio:** Dado el diccionario `{"a": 1, "b": 2, "c": 3}`, elimina la clave "b". Imprime el diccionario actualizado.
- **Solución:**
  ```python
  diccionario = {"a": 1, "b": 2, "c": 3}
  del diccionario["b"]
  print(diccionario)
  ```

**Ejercicio 5:**
- **Ejercicio:** Dada la lista `[4, 7, 2, 8, 3]`, ordénala en orden ascendente. Imprime la lista ordenada.
- **Solución:**
  ```python
  lista = [4, 7, 2, 8, 3]
  lista.sort()
  print(lista)
  ```
[Volver a la página del temario](https://github.com/maca-chan/python-ejercicios/tree/main)
