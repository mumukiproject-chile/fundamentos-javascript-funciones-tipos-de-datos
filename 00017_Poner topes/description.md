_Hagamos un alto en nuestro camino y miremos las funciones `Math.max` y `Math.min`, que nos pueden ahorrar más trabajo de lo que parece_.

Necesitamos una función que diga cuánta plata queda en tu cuenta (que tiene un cierto `saldo`) si extraes un cierto `monto`:

```javascript
// el saldo es $10.000, el monto a extraer, $3.000
ム extraer(10.000, 3.000) 
7.000 //quedan $7.000 ($10.000 - $3.000 =  $7.000) 
```

Pero como no queremos quedarnos en negativo, si el monto a extraer es mayor al saldo, nuestro saldo debe quedar en cero.

```javascript
ム extraer(10.000, 12.000)
0 //Ups, quisimos sacar más plata de la que teníamos. 
  //Nos quedamos con $0
```

Como ves, esto es _casi_ una resta entre `saldo` y `monto`, con la salvedad de que estamos poniendo un _tope inferior_: no puede dar menos de cero :open_mouth:.

En otras palabras (¡prepárate!, esto te puede volar la cabeza :bomb:), `extraer` **devuelve el máximo** entre la resta `saldo - monto`  y `0`.

> ¿Te animas a completar la solución que está en el editor? 
