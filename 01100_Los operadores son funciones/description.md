Pasajeros, ¡ajústense los cinturones porque tiraremos una bomba! :bomb:

¿Preparado? ¿Listo? Ahí va: los operadores que vimos antes, como la suma (`+`), resta (`-`), multiplicación (`*`), ¡son funciones!. :boom:

Solo que son un poco especiales, porque sus nombres no son una palabra (como lo es `siguiente`), sino un "chirimbolo".

Además, mientras que

  * las funciones comunes se aplican de forma _prefija_ (es decir, delante de sus argumentos): `siguiente numero`
  * los operadores se utilizan de forma _infija_ (es decir, entre medio de sus argumentos): `3 + numero`

¿No nos crees? Haskell nos permite también usar a los operadores de forma prefija, poniendo en evidencia que son funciones, si los ponemos entre paréntesis, así:

```haskell
siguiente numero = (+) numero 1
```

Aunque en general es más difícil de leer y por eso lo veníamos evitando, a veces esto nos permitirá salvar las papas del fuego.

> Veamos si se entiende: escribí la función doble, pero esta vez utilizando al operador `*` de forma prefija.

