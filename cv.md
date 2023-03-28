# Diyor Baynazarov

## Support Specialist

---

### Contact information:

**Email:** diyor.baynazarov2000@gmail.com

**Telegram:** @U1910235_Diyor_Baynazarov

[**LinkedIn**](https://www.linkedin.com/in/diyor-baynazarov-019604176/)

---

### About me:

On a mission to become a full-stack developer - no-code experience + front-end roadmap. Ready to take on any challenge and create something amazing!

Technical problem solver and no-code developer in the past job and I was helping businesses build products without writing a single line of code.
Providing top-notch support for customers facing technical issues is my current position.

Tech enthusiast and problem-solver. Learning something new every day. HTML, CSS, JS, React and Node/Express coder. Math, physics and Spanish lover. Always eager to read a good book!

---

### Skills:

- Markup and Style Sheet Languages
  - HTML
  - CSS
- Programming Languages
  - JavaScript
  - SQL (Domain specific)
- Libraries and Frameworks
  - React
  - Express
- DBMS
  - Postgres
- Version Contol Systems
  - Git
- IDE
  - VS Code

---

### Code:

**Task - Sum without highest and lowest number.**

Description - Sum all the numbers of a given array, except the highest and the lowest element (by value, not by index!). The highest or lowest element respectively is a single element at each edge, even if there are more than one with the same value. Mind the input validation.

```
function sumArray(array) {
  if (!array || !array.length || array.length <= 2) return 0;
  let minI = array.indexOf(Math.min(...array));
  let maxI = array.indexOf(Math.max(...array));
  let sum = 0;

  for (let i = 0; i < array.length; i++) {
    if (i !== minI && i !== maxI) {
      sum += array[i];
    }
  }

  return sum;
}
```
