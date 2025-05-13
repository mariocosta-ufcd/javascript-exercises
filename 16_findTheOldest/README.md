# Exercício 16 - Encontrar a Pessoa Mais Velha 👵🧓

Recebes um array de objetos que representam pessoas com ano de nascimento e, opcionalmente, ano de morte.  
O teu objetivo é **encontrar a pessoa mais velha** com base na idade que viveu.

---

## 🧪 O que deves devolver

- A função deve **devolver o objeto completo** da pessoa mais velha.
- Os testes verificam principalmente se o nome da pessoa está correto.

---

## 💡 Dicas

- Podes usar `.reduce()` para comparar idades e manter a pessoa mais velha encontrada até ao momento.
- Algumas pessoas não têm `yearOfDeath` — nesses casos, assume que ainda estão vivas e calcula a idade até ao ano atual:
  ```javascript
  const currentYear = new Date().getFullYear();
  ```

- A idade pode ser calculada assim:
  ```javascript
  const age = (person.yearOfDeath || currentYear) - person.yearOfBirth;
  ```

---

Este é o último exercício! 🏁  
Aplica tudo o que aprendeste sobre **arrays**, **objetos**, **funções**, **condições** e **métodos como `.reduce()`**.  
Boa sorte — e parabéns por chegares até aqui! 🚀🎉
