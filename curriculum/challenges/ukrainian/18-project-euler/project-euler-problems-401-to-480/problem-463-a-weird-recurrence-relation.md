---
id: 5900f53c1000cf542c51004e
title: 'Завдання 463: дивне рекурентне співвідношення'
challengeType: 1
forumTopicId: 302138
dashedName: problem-463-a-weird-recurrence-relation
---

# --description--

Функцію $f$ визначено для натуральних чисел таким чином:

$$\begin{align}   & f(1) = 1 \\\\
  & f(3) = 3 \\\\   & f(2n) = f(n) \\\\
  & f(4n + 1) = 2f(2n + 1) - f(n) \\\\ & f(4n + 3) = 3f(2n + 1) - 2f(n) \end{align}$$

Функцію $S(n)$ визначено як $\sum_{i=1}^{n} f(i)$.

$S(8) = 22$ та $S(100) = 3604$.

Знайдіть $S(3^{37})$. У відповіді запишіть 9 останніх цифр.

# --hints--

`weirdRecurrenceRelation()` має повернути `808981553`.

```js
assert.strictEqual(weirdRecurrenceRelation(), 808981553);
```

# --seed--

## --seed-contents--

```js
function weirdRecurrenceRelation() {

  return true;
}

weirdRecurrenceRelation();
```

# --solutions--

```js
// solution required
```
