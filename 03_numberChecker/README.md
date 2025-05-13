# Exercise 03 - numberChecker

Neste exercício vais corrigir a função numberChecker para que devolva true se o número for maior ou igual a 10, e false caso contrário.

### ❌ Problema atual

Neste momento, a função está errada:
Ela devolve true apenas quando o número é 6, e false para os restantes valores.

### ✅ O que tens de fazer
- Edita apenas a linha 2 da função.
- A função deve verificar se o número recebido é maior ou igual a 10 (>= 10).
- Não cries condições para cada número individual. Usa operadores de comparação.

### 🧪 Como testar
1. Corre no terminal:
```bash
npm numberChecker.spec.js
```
2. No ficheiro numberChecker.spec.js vais ver vários testes.
3. **Só o primeiro está ativado no início**. Quando esse funcionar:
  - Apaga .skip da próxima linha: `test.skip(...)`
  - Muda para: `test(...)`
4. **Vai ativando um teste de cada vez** e corrige o código até todos passarem!

### 📌 Exemplo do que pode aparecer:

````yaml
Test Suites: 1 passed, 1 total
Tests:       3 skipped, 1 passed, 4 total
```
Isso significa que só um teste está ativo. Quando terminares, deves ter 4 testes a passar.

### 💡 Dicas
- Lembra-te: só precisas de alterar uma linha.
- Pesquisa por operadores de comparação em JavaScript se tiveres dúvidas: >=, <, ===, etc.