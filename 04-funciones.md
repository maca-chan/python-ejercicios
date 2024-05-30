# Ejercicios de Python para aprender a implementar funciones
[Volver a la página del temario](https://github.com/maca-chan/python-ejercicios/tree/main)

**Ejercicio 1:**
- **Ejercicio:** Escribe una función `suma(a, b)` que tome dos números y devuelva su suma.
- **Solución:**
  ```python
  def suma(a, b):
      return a + b

  resultado = suma(3, 4)
  print(f"La suma es: {resultado}")
  ```

**Ejercicio 2:**
- **Ejercicio:** Escribe una función `es_par(n)` que tome un número y devuelva `True` si es par, y `False` si es impar.
- **Solución:**
  ```python
  def es_par(n):
      return n % 2 == 0

  numero = 4
  print(f"El número {numero} es par: {es_par(numero)}")
  ```

**Ejercicio 3:**
- **Ejercicio:** Escribe una función mayusculas(cadena) que tome una cadena de texto y devuelva la cadena en mayúsculas.
- **Solución:**
  ```python
  def mayusculas(cadena):
      return cadena.upper()

  print(mayusculas("hola mundo"))  # HOLA MUNDO

  ```

**Ejercicio 4:**
- **Ejercicio:** Escribe una función `saludo(nombre)` que tome un nombre como entrada y imprima un saludo personalizado.
- **Solución:**
  ```python
  def saludo(nombre):
      print(f"Hola, {nombre}!")

  saludo("Carlos")
  ```

**Ejercicio 5:**
- **Ejercicio:** Escribe una función `maximo(lista)` que tome una lista de números y devuelva el número más grande.
- **Solución:**
  ```python
  def maximo(lista):
      max_num = lista[0]
      for num in lista:
          if num > max_num:
              max_num = num
      return max_num

  numeros = [3, 5, 7, 2, 8]
  print(f"El número más grande es: {maximo(numeros)}")
  ```

[Volver a la página del temario](https://github.com/maca-chan/python-ejercicios/tree/main)
