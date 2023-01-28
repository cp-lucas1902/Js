# Js

I hope it helps !

## Reduce

`:reduce() ` O método reduce() executa uma função reducer (fornecida por você) para cada elemento do array, resultando num único valor de retorno.

```js
[0, 1, 2, 3, 4].reduce(function(acumulador, valorAtual, index, array) {
  return acumulador + valorAtual;
});
// 10
```

A função reducer recebe quatro parâmetros:

Acumulador `:(acc) `
Valor Atual `:(cur)`
Index Atual `:(idx)`
Array original `:(src)`

```js
const array1 = [1, 2, 3, 4];

// 0 + 1 + 2 + 3 + 4
const initialValue = 0;
const sumWithInitial = array1.reduce(
  (accumulator, currentValue) => accumulator + currentValue,
  initialValue
);

console.log(sumWithInitial);
// Expected output: 10
```

