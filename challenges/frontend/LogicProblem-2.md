# Weso Studio | Tech Challenge

Este es un desafío para formar un palíndromo navideño.

**Un palíndromo es una palabra que se lee igual hacia adelante y hacia atrás.**  Queremos saber si es posible formar un palíndromo haciendo, como mucho, un intercambio de letras.

Crea una función  `getIndexsForPalindrome`  que reciba una cadena de caracteres y devolverá:

-   Si ya es un palíndromo, un array vacío.
-   Si no es posible, null.
-   Si se puede formar un palíndromo con un cambio, un array con las dos posiciones (índices) que se deben intercambiar para poder crearlo.

Por ejemplo:

```javascript
getIndexsForPalindrome('anna') // []
getIndexsForPalindrome('abab') // [0, 1]
getIndexsForPalindrome('abac') // null
getIndexsForPalindrome('aaaaaaaa') // []
getIndexsForPalindrome('aaababa') // [1, 3]
getIndexsForPalindrome('caababa') // null

```

Si se puede formar el palíndromo con diferentes intercambios,  **siempre se debe devolver el primero que se encuentre.**