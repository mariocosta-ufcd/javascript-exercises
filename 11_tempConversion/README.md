# Exercício 11 - Conversão de Temperaturas 🌡️

Neste exercício vais criar **duas funções** para converter temperaturas entre Fahrenheit e Celsius.

---

## 🔁 O que fazer

Cria as seguintes funções:

```javascript
convertToCelsius(32) // converte de Fahrenheit para Celsius → deve devolver 0
convertToFahrenheit(0) // converte de Celsius para Fahrenheit → deve devolver 32
```

---

## 🎯 Requisitos

- O resultado deve ser **arredondado para uma casa decimal**.
  - Exemplo:
    ```javascript
    convertToCelsius(100) // deve devolver 37.8 (e não 37.777777...)
    ```

---

## 📦 Nota sobre `module.exports`

Este exercício tem mais do que uma função, por isso o `module.exports` no final do ficheiro `.js` estará um pouco diferente.  
Não te preocupes — apenas estamos a **agrupar as duas funções num objeto** para exportar.

---

## 💡 Dicas

- As fórmulas de conversão estão na [Wikipedia](https://pt.wikipedia.org/wiki/Convers%C3%A3o_de_unidades_de_temperatura)
- Para arredondar um número a 1 casa decimal em JavaScript:
  ```javascript
  Math.round(valor * 10) / 10
  ```
  Ou, se quiseres uma string com formato:
  ```javascript
  valor.toFixed(1)
  ```

---

Boa sorte! Este exercício vai ajudar-te a praticar **operações matemáticas**, **funções múltiplas** e **arredondamentos** 🧠➕📐
