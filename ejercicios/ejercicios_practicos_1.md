## 1) Caja registradora básica

En una tienda compras **3 productos**.
Pide el **precio** de cada producto y muestra:

* Total sin IVA
* IVA (19%)
* Total con IVA

---

## 2) Nota final (promedio simple)

Un estudiante tiene 3 notas (0 a 5).
Pide `n1`, `n2`, `n3` y muestra:

* Promedio
* Mensaje: “Promedio calculado: X” (solo mostrar, sin evaluar si pasó o no)

---

## 3) Nota final (ponderado)

En una materia:

* Talleres 30%
* Parcial 30%
* Proyecto 40%
  Pide las 3 notas y calcula la **nota final ponderada**.

---

## 4) Conversor de temperatura para laboratorio

En un laboratorio registran temperatura en °C.
Pide `celsius` y muestra:

* Fahrenheit
* Kelvin
  Usa: `F = (C * 9/5) + 32`, `K = C + 273.15`

---

## 5) Rectángulo: material para marco

Quieres construir un marco rectangular.
Pide `base` y `altura` (en cm) y muestra:

* Área (cm²)
* Perímetro (cm)
* Metros de cinta necesarios para el borde (perímetro / 100)

---

## 6) Círculo: etiqueta redonda

Vas a imprimir una etiqueta circular.
Pide `radio` (cm), usa `pi = 3.1416` y muestra:

* Área
* Circunferencia

---

## 7) Distancia entre dos puntos (mapa)

Para ubicar dos lugares en un plano, piden coordenadas.
Pide `x1, y1, x2, y2` y calcula la distancia:
`d = ((x2-x1)^2 + (y2-y1)^2)^(1/2)`
Muestra la distancia.

---

## 8) Tiempo total en segundos (video)

Un video dura `h` horas, `m` minutos y `s` segundos.
Pide esos valores y muestra:

* Duración total en segundos

---

## 9) Precio final con descuento

Una tienda aplica descuento por promoción.
Pide:

* `precio_base`
* `descuento` (porcentaje, por ejemplo 15 para 15%)
  Muestra:
* Valor del descuento
* Precio final

---

## 10) Descuento + IVA (dos pasos)

Un producto tiene descuento y luego se le aplica IVA.
Pide:

* `precio_base`
* `descuento` (%)
* `iva` (%)
  Muestra:
* Subtotal con descuento
* Valor del IVA
* Total final

---

## 11) Nómina simple

A un empleado le pagan:

* `horas_trabajadas`
* `valor_hora`
  Además recibe un `bono` fijo y le descuentan `descuento` fijo.
  Muestra:
* Salario bruto = horas*valor_hora
* Total a pagar = bruto + bono − descuento

---

## 12) Conversión de moneda (viaje)

Vas a comprar dólares para un viaje.
Pide:

* `cop` (pesos colombianos)
* `tasa` (cuántos COP vale 1 USD)
  Muestra cuántos USD puedes comprar (con decimales).

---

## 13) Extraer dígitos (3 cifras)

Pide un número entero de **3 cifras** (ej: 583).
Calcula y muestra por separado:

* Centenas
* Decenas
* Unidades
  Pista: usa `//` y `%`.

---

## 14) Invertir un número (3 cifras)

Pide un número entero de 3 cifras (ej: 472).
Usando los dígitos (como en el anterior), arma el número invertido (274).
Muestra el original y el invertido.

---

## 15) Validaciones con booleanos (sin if)

Pide `a`, `b`, `c` y muestra el resultado (`True` o `False`) de estas expresiones:

* `a` es mayor que `b`
* `b` es igual a `c`
* `a` es diferente de `c`
* `a` está entre 0 y 100 (incluidos)
* `a` es mayor que `b` y `b` es mayor que `c`

*(Solo imprimir los resultados, no tomar decisiones).*

---
