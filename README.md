## controles de flujo de decicionesw en python ##
**Control de flujo**

Python, como el resto de los lenguajes de programación, tenemos varios modos de controlar el flujo del programa.
En Python tenemos tres modos elementos para controlar el flujo:
La declaración if, que ejecuta un bloque particular de comandos en función del resultado de un test.
La declaración while, que ejecuta un bloque de comandos mientras que se cumpla un test determinado.
La declaración for loop, que ejecuta un bloque de comandos un cierto número de veces.
En Python es "obligatorio" definir una estructura de control del siguiente modo:
inicio de la estructura de control:
    expresiones
Es obligatoria la IDENTACIÓN, que no es otra cosa que realizar una sangría de 4 espacios en blanco.
Recuerda siempre que en Python la identación es obligatoria
>ejemplo:
```python
num = 8
if num % 2 == 0:
    print('El número {} es par'.format(num))
else:
    print('El número {} es impar'.format(num))
```