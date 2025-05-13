# Exercício 13 - Palíndromos 🔁

Escreve uma função que determina se uma determinada string é um **palíndromo**.

---

## ❓ O que é um palíndromo?

Um palíndromo é uma palavra ou frase que se lê **da mesma forma de trás para a frente**, ignorando pontuação, espaços e maiúsculas/minúsculas.

### Exemplos de palíndromos:

- A car, a man, a maraca.
- Rats live on no evil star.
- Lid off a daffodil.
- Animal loots foliated detail of stool lamina.
- A nut for a jar of tuna.

---

## 🧪 Exemplos

```javascript
palindromes('racecar') // true
palindromes('tacos')   // false
```

---

## 💡 Dicas

- Ignora **espaços**, **pontuação** e **maiúsculas/minúsculas**.
- Podes:
  1. Converter a string para lowercase
  2. Remover todos os caracteres não alfabéticos
  3. Inverter a string e compará-la com a original

Exemplo de abordagem:
```javascript
const cleaned = string.toLowerCase().replace(/[^a-z]/g, '');
const reversed = cleaned.split('').reverse().join('');
return cleaned === reversed;
```

---

Este exercício é excelente para treinar manipulação de strings e expressões regulares. Boa sorte! 🚀
