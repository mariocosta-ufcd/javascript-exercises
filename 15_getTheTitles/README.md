# Exercício 15 - Obter os Títulos! 📚

Recebes um array de objetos que representam livros, com `title` e `author`.  
A tua tarefa é criar uma função que devolve **apenas os títulos dos livros**.

---

## 🧪 Exemplo

```javascript
const books = [
  { title: 'Book', author: 'Name' },
  { title: 'Book2', author: 'Name2' }
];

getTheTitles(books); // devolve ['Book', 'Book2']
```

---

## 💡 Dicas

- Usa um **método embutido do JavaScript** para facilitar o trabalho.
- O método `.map()` é ideal para **transformar arrays** — neste caso, para extrair os títulos de cada objeto.

Exemplo de estrutura:
```javascript
return books.map(book => book.title);
```

---

Este exercício ajuda-te a praticar a manipulação de arrays de objetos — algo muito comum no desenvolvimento web moderno. Boa sorte! 🚀
