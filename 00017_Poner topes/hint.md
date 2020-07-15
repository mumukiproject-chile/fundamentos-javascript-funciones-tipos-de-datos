¿No estás convencido de que el máximo entre `saldo - monto`  y `0` resuelve nuestro problema? Compara estos ejemplos con los dos anteriores:

```javascript
ム Math.max(10.000 - 3.000, 0)
7.000 // da el máximo entre 7.000 y 0, que es 7.000  

ム Math.max(10.000 - 12.000, 0)
0 // da el máximo entre -2.000 y 0, que es 0
```


