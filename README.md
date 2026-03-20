# 🔽 Números del 10 al 1 - Multilenguaje (Pascal + C++ + Python)

## 📌 Descripción

Este proyecto es un programa simple desarrollado en **Pascal**, **C++** y **Python** que imprime en pantalla los números del **10 al 1** en orden descendente.

---

## ⚙️ Funcionamiento

Todas las versiones del programa:

1. Usan un bucle para recorrer del 10 al 1.
2. Imprimen cada número en la misma línea.
3. Separan los valores con espacios.
4. Finalizan con un salto de línea.

---

## 💻 Código en Pascal

```pascal
program numero10al1;
var i: Integer;
begin
 for i := 10 downto 1 do
  write(i, ' ');
 writeln(' ')
end.
```

---

## 💻 Código en C++

```cpp
#include <iostream>

int main() {
 for (int i = 10; i >= 1; i--) {
  std::cout << i << ' ';
 }
 std::cout << '\n';
}
```

---

## 💻 Código en Python

```python
for i in range(10, 0, -1):
    print(i, end=' ')

print()
```

---

## ▶️ Ejecución

### Pascal (Free Pascal)

```bash
fpc numero10al1.pas
./numero10al1
```

### C++

```bash
g++ numero10al1.cpp -o numero10al1
./numero10al1
```

### Python

```bash
python numero10al1.py
```

---

## 🧾 Salida esperada

```
10 9 8 7 6 5 4 3 2 1
```

---

## 🎯 Objetivo del proyecto

* Practicar bucles descendentes
* Comparar sintaxis entre lenguajes
* Entender iteraciones inversas

---

## 🚀 Futuras mejoras

* Agregar más lenguajes (Java, JavaScript… que esto ya es una bajada internacional 📉)
* Permitir definir el rango dinámicamente
* Versiones con funciones reutilizables

---

## 📂 Estructura del proyecto

```
/numero10al1
 ├── numero10al1.pas
 ├── numero10al1.cpp
 ├── numero10al1.py
 └── README.md
```

---

## 📜 Licencia

Uso libre con fines educativos.
