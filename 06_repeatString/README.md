# Exercício 06 - Repetir String 🔁

Escreve uma função que repete uma string um determinado número de vezes.  
Exemplo:

```javascript
repeatString('hey', 3) // devolve 'heyheyhey'
```

---

## ✅ O que a função deve fazer

A função `repeatString` deve receber **dois argumentos**:
- `string`: o texto a repetir
- `num`: o número de vezes que deve ser repetido

Deves usar **um ciclo (loop)** para implementar a função — **não podes usar `String.prototype.repeat()`**, mesmo que tenha o mesmo comportamento.

---

## 💡 Dicas

- Cria uma variável que começa com uma string vazia (por exemplo `let resultado = ''`)
- Usa um ciclo `for` ou `while` para repetir o número de vezes indicado por `num`
- Em cada volta do ciclo, junta a string ao resultado (`resultado += string`)

---

## 🧪 Exemplo de teste

```javascript
repeatString('hey', 3) // deve devolver 'heyheyhey'
```

---

## ⚠️ Nota importante

A partir deste exercício, os argumentos **já não serão fornecidos automaticamente** como neste exemplo.

Lê com atenção o `README.md` de cada exercício para perceber **que argumentos** deves passar à função durante os testes.

---

Bom trabalho! Continua a praticar — estás quase a dominar ciclos e funções! 🚀
