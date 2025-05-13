# Exercício 10 - Anos Bissextos 📅

Cria uma função chamada `leapYears` que determina se um determinado ano é **bissexto** ou não.

## 📖 Regras:

- Anos divisíveis por **4** são bissextos  
  ✅ Ex: 1984, 2004

- MAS anos divisíveis por **100** **não** são bissextos  
  ❌ Ex: 1800, 1900

- EXCEPTO se também forem divisíveis por **400**  
  ✅ Ex: 1600, 2000

---

## 🧪 Exemplos

```javascript
leapYears(2000) // true - é bissexto
leapYears(1985) // false - não é bissexto
```

Se ainda estiveres confuso, consulta este resumo:  
[time-and-calendar.com - Leap Years](https://time-and-calendar.com/leap-years/#:~:text=How%20to%20Know%20if%20Certain%20Year%20is%20a%20Leap%20Year)

---

## 💡 Dicas

- Usa um `if` com operadores lógicos como `&&` e `||`
- Lembra-te de testar as condições pela ordem correta:
  1. Divisível por 400 → ✅ é bissexto
  2. Divisível por 100 → ❌ não é bissexto
  3. Divisível por 4 → ✅ é bissexto

---

Boa sorte! Este é um ótimo exercício para praticar **condições múltiplas e lógica booleana**! 🧠
