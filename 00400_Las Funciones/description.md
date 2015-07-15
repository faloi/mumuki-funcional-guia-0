Estamos aprendiendo sobre el paradigma **funnnnnn**cional... ¡adiviná cuál es otro elemento fundamental del paradigma! ¡Las funciones!

La idea es simple: una función es una **caja negra**, a la que entra algo, y de la que sale otra cosa:

![blackbox.png](https://raw.githubusercontent.com/pdep-utn/mumuki-funcional-guia-0/master/images/blackbox.png)

Por ejemplo, una función muy simple es la que calcula el _siguiente_ de un número, esto es, el número original más 1:

![blackbox_succ.png](https://raw.githubusercontent.com/pdep-utn/mumuki-funcional-guia-0/master/images/blackbox_succ.png)

A una función podemos ponerle a su entrada un valor, lo que se conoce como **aplicar la función**, y al hacerlo obtenemos un salida correspondiente. Veamos ejemplos: si a esta función `siguiente`la aplicamos con:

* el número 1, obtendremos a su salida el numero 2
* el número 10, obtendremos a su salida el numero 11
* etc

¿Fácil, no? En Haskell esta función se escribe así:

```haskell
siguiente numero = numero + 1
```

> ¿Te imaginás como se escribirá una función que calcule el anterior, es decir, el número de la entrada, menos 1? ¡Escribilo!
