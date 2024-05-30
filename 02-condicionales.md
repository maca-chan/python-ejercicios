# Ejercicios de Python para aprender a usar Estructuras condicionales
[Volver a la página del temario](https://github.com/maca-chan/python-ejercicios/tree/main)

**Ejercicio 1:**
- **Ejercicio:** Escribe unas líneas de código que determinen si un número es positivo, negativo o cero.
- **Solución:**
  ```python
  numero = float(input("Introduce un número: "))
  if numero > 0:
      print("El número es positivo.")
  elif numero < 0:
      print("El número es negativo.")
  else:
      print("El número es cero.")
  ```

**Ejercicio 2:**
- **Ejercicio:** Escribe un script que determine si un año es bisiesto. **Nota**: un año es bisiesto si es divisible por 4, pero no por 100, excepto si es divisible por 400.
- **Solución:**
  ```python
  año = int(input("Introduce un año: "))
  if (año % 4 == 0 and año % 100 != 0) or (año % 400 == 0):
      print("El año es bisiesto.")
  else:
      print("El año no es bisiesto.")
  ```

**Ejercicio 3:**
- **Ejercicio:** Escribe un script que tome una letra como entrada y determine si es una vocal o una consonante.
- **Solución:**
  ```python
  letra = input("Introduce una letra: ").lower()
  if letra in "aeiou":
      print("Es una vocal.")
  else:
      print("Es una consonante.")
  ```

**Ejercicio 4:**
- **Ejercicio:** Escribe un programa que tome tres números y determine cuál es el mayor.
- **Solución:**
  ```python
  num1 = float(input("Introduce el primer número: "))
  num2 = float(input("Introduce el segundo número: "))
  num3 = float(input("Introduce el tercer número: "))
  if num1 >= num2 and num1 >= num3:
      mayor = num1
  elif num2 >= num1 and num2 >= num3:
      mayor = num2
  else:
      mayor = num3
  print(f"El número mayor es: {mayor}")
  ```

**Ejercicio 5:**
- **Ejercicio:** Escribe un programa que determine si una persona es mayor de edad (18 años o más) usando los datos de entrada del terminal.
- **Solución:**
  ```python
  edad = int(input("Introduce tu edad: "))
  if edad >= 18:
      print("Eres mayor de edad.")
  else:
      print("No eres mayor de edad.")
  ```


[Volver a la página del temario](https://github.com/maca-chan/python-ejercicios/tree/main)
