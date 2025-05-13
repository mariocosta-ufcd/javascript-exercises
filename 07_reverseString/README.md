# Exercício 07 - Inverter uma String 🔁

Este é simples: escreve uma função chamada `reverseString` que devolve a string ao contrário.

Exemplo:

```javascript
reverseString('hello there') // devolve 'ereht olleh'
```

---

## ✅ O que fazer

- A função deve aceitar **uma string** como argumento.
- Deve devolver essa string **invertida**.

---

## 🔍 Como testar

No ficheiro `reverseString.spec.js` existem **vários testes**.

1. Só o **primeiro teste** está ativo no início.
2. Quando o primeiro passar, **ativa os seguintes** removendo `.skip`:
   ```javascript
   test.skip(...)
   ```
   muda para:
   ```javascript
   test(...)
   ```
3. Vai ativando **um de cada vez** até todos passarem ✅

---

## 💡 Dicas

- Em JavaScript **não podes inverter diretamente uma string**.
- Mas podes:
  1. Usar `.split('')` para transformá-la num array de letras
  2. Usar `.reverse()` para inverter o array
  3. Usar `.join('')` para voltar a juntar tudo numa string

Exemplo de ideia base:
```javascript
return string.split('').reverse().join('');
```

---

Boa sorte! Este exercício é ótimo para treinar manipulação de strings e arrays! 🚀
