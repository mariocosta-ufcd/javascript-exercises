Exercício 01 - Hello World 🌍
O objetivo principal deste exercício é garantir que tudo está bem configurado e a funcionar no teu ambiente. Vais aprender a correr os testes automáticos e a interpretar o que eles te pedem.

Neste diretório vais encontrar 2 ficheiros:

helloWorld.js

helloWorld.spec.js

Este tipo de estrutura será igual para os próximos exercícios:

O ficheiro .js normal é onde vais escrever o teu código.

O ficheiro .spec.js contém os testes automáticos que verificam se o teu código está correto.

-----

### 🔍 O que está no ficheiro de teste?

```javascript
const helloWorld = require('./helloWorld');

describe('Hello World', function() {
  test('says "Hello, World!"', function() {
    expect(helloWorld()).toEqual('Hello, World!');
  });
});
```
- A primeira linha (require) importa a tua função de helloWorld.js.
- O resto é o teste: basicamente, ele chama a tua função e verifica se o resultado está certo.
- Neste caso, o teste espera que a função helloWorld() devolva exatamente a frase: "Hello, World!"

-----
### 🧪 Como correr os testes?
Abre o terminal na pasta deste exercício e escreve:
```bash
npm test helloWord.spec.js
```
O teste vai falhar de propósito no início — isso é normal!
A mensagem que aparecer no terminal vai dizer o que está errado.

-----
### 👨‍💻 Olhando para o ficheiro helloWorld.js

```javascript
const helloWorld = function() {
  return ''
}

module.exports = helloWorld
```

- Neste ficheiro, tens uma função que devolve uma string vazia.
- O teste espera que ela devolva "Hello, World!".

Tenta alterar a função para passar no teste.
Lembra-te: **letras maiúsculas, pontuação e espaços contam!**

-----

### ✅ Solução esperada
Se precisares de uma ajuda, aqui está como a função correta deve ficar:
```javascript
const helloWorld = function() {
  return 'Hello, World!'
}

module.exports = helloWorld
```

-----
### ℹ️ Dicas Finais

- Não te preocupes com require() ou module.exports por agora — isso já está tratado para ti.

- Concentra-te apenas em escrever o código dentro da função.

- O importante é fazer os testes passarem ✅

Bom trabalho! Continua a praticar — estás no caminho certo para te tornares um mestre do JavaScript! 🚀