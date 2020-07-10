Como acabamos de ver, en JavaScript existen números, booleanos y strings:

| Tipo de dato | Representa        | Ejemplo  | Operaciones                     |
| ------------ | ----------------- | -------- | ------------------------------- |
| Número       | cantidades        | `4947`   | `+`, `-`, `*`, `%`, `<`, etc |
| Booleano     | valores de verdad | `true`   | `&&`, `!`, etc          |
| String       | texto             | `"hola"` | `longitud`, `comienzaCon`, etc  |


Además, existen operaciones que sirven para todos los _tipos de datos_, por ejemplo:

* `===`: nos dice si dos cosas son iguales
* `!==`: nos dice si dos cosas son diferentes

**Es importante usar las operaciones correctas con los tipos de datos correctos**. Por ejemplo, no tiene sentido sumar dos booleanos o hacer operaciones booleanas con los números. **Si usas operaciones que no corresponden, pueden pasar cosas muy raras y malas**. :confounded:

> Prueba en la consola las siguientes cosas:
> 
> * `5 + 6` (OK, los números se pueden sumar.)
> * `5 === 6` (OK, todas las cosas se pueden comparar.)
> * `8 > 6` (OK, los números se pueden ordenar.)
> * `!true` (OK, los booleanos se pueden _negar_.)
> * `false / true` (No está bien, ¡los booleanos no se pueden dividir!)

