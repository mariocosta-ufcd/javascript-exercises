# Exercício 08 - Remover de um Array ❌📦

Implementa uma função chamada `removeFromArray` que recebe um array e um ou mais valores, e devolve um novo array **sem esses valores**.

Exemplo:

```javascript
removeFromArray([1, 2, 3, 4], 3); // deve devolver [1, 2, 4]
```

---

## ✅ O que fazer

- A função recebe:
  - Um array (por exemplo `[1, 2, 3, 4]`)
  - Um ou mais valores a remover (ex: `3`, `2`, etc.)
- Devolve um **novo array** sem os valores indicados.

---

## 💡 Dicas

- O primeiro teste é fácil, mas os seguintes vão exigir mais atenção.
- Podes:
  - Manipular o array original OU
  - Criar um novo array e devolvê-lo
- Vais precisar de:
  - Saber **remover elementos de um array**
  - Lidar com **vários argumentos na função**

🔎 Pesquisa sobre:
- `function(...args)` (rest parameters)
- `Array.prototype.filter()`
- `Array.from(arguments)` (menos moderno)

Documentação útil:
- [Parâmetros Rest (MDN)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [Argumentos de função (MDN)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Functions/arguments)

---

Boa sorte! Este exercício é excelente para aprender a trabalhar com arrays e múltiplos argumentos em funções 🚀
