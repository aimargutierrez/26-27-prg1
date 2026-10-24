# Reto 002 – Reto extendido: predicción

**Caso:** el cliente debe pagar 232 € y entrega 200 €
## Predicción (antes de ejecutar)

El programa no comprueba nada, así que calculará `resto = 200 - 232 = -32` y seguirá dividiendo.
En Java la división entera trunca hacia cero y `%` conserva el signo del dividendo, por lo que
creo que saldrá algo así:

```
0 billete(s) de 100 €
0 billete(s) de 50 €
-1 billete(s) de 20 €
-1 billete(s) de 10 €
0 billete(s) de 5 €
-1 moneda(s) de 2 €
0 moneda(s) de 1 €
```

Es decir, cantidades negativas: -20 - 10 - 2 = -32.
