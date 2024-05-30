# Ejercicios de Python para aprender a usar Bucles for y while

**Ejercicio 1:**
- **Ejercicio:** Usa un bucle `for` para imprimir los números del 1 al 5.
- **Solución:**
  ```python
  for i in range(1, 6):
      print(i)
  ```

**Ejercicio 2:**
- **Ejercicio:** Usa un bucle `while` para imprimir los números del 1 al 5.
- **Solución:**
  ```python
  i = 1
  while i <= 5:
      print(i)
      i += 1
  ```

**Ejercicio 3:**
- **Ejercicio:** Usa un bucle `for` para recorrer la lista `["manzana", "banana", "cereza"]` e imprimir cada elemento.
- **Solución:**
  ```python
  frutas = ["manzana", "banana", "cereza"]
  for fruta in frutas:
      print(fruta)
  ```

**Ejercicio 4:**
- **Ejercicio:** Usa un bucle `while` para sumar los números del 1 al 10.
- **Solución:**
  ```python
  suma = 0
  i = 1
  while i <= 10:
      suma += i
      i += 1
  print(f"La suma es: {suma}")
  ```

**Ejercicio 5:**
- **Ejercicio:** Usa un bucle `for` para imprimir los números pares del 1 al 10.
- **Solución:**
  ```python
  for i in range(1, 11):
      if i % 2 == 0:
          print(i)
  ```

