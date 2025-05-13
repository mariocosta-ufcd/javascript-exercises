# Exercício 05 - Juntar Strings 🧩

## Etapa 1: Aprender

Primeiro, analisa o código de exemplo no ficheiro `joinStrings-example.js`.  
Tenta prever o que vai aparecer no `console.log`. Quando estiveres pronto, corre o teste:

```bash
npm test joinStrings-example.spec.js
```

Se o resultado não for o que esperavas, volta a rever o código com atenção.

---

## Etapa 2: Fazer

Depois de perceberes o exemplo, vais recriar o código por ti, seguindo estas instruções no ficheiro `joinStrings.js`:

1. Cria 4 variáveis: `firstName`, `lastName`, `thisYear` e `birthYear`

2. Cria uma 5ª variável chamada `greeting` construída a partir das 4 anteriores:
   - Deve conter uma mensagem de saudação com o **nome completo** e a **idade** da pessoa.

⚠️ **Atenção:** Para que os testes passem, tens de usar **valores e palavras exatamente como descrito** no ficheiro `joinStrings.js`.  
Se os testes falharem, lê bem a mensagem no terminal e verifica **os espaços, letras maiúsculas e pontuação**.

---

## Etapa 3: Otimizar

Agora vais melhorar o teu código, tornando-o mais legível, seguindo estas instruções:

1. Cria 2 novas variáveis: `fullName` e `age`
   - ❌ NÃO escrevas diretamente o nome completo nem a idade.
   - ✅ Usa as variáveis existentes e faz os cálculos/concatenações nelas.

2. Altera a string `greeting` para usar `fullName` e `age` em vez das 4 variáveis originais.
   - A `greeting` deve ficar parecida com:
```js
"Hello! My name is " + fullName
```

Corre todos os testes mais uma vez para garantir que a saída continua igual:

```bash
npm test joinStrings.spec.js
```

---

## 💡 Dicas

- Consulta a documentação sobre variáveis em JavaScript se precisares de ajuda.

- Relembra a lição sobre `Variáveis e Operadores`

Bom trabalho! Estás a ficar cada vez melhor com JavaScript! 🚀
