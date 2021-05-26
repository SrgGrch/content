---
tags:
  - practice
permalink: false
---

🛠 Из-за того, что результат выполнения метода `Array.every` – это boolean-значение, то метод можно удобно иcпользовать прямо в условных конструкциях

```js
const drinks = ['🍺', '🍺', '🍺', '🍺', '🍺']

if (drinks.every(drink => drink === '🍺')) {
  console.log('This is a beer party! 🎉')
}
```