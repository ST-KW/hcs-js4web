# hcs-js4web
Exercises in the JavaScript for Web Course at the Hamburg Coding School

1. What's the value of `result`?

```js
const badlyNamedFunction = (a, b) => a + b

const result = badlyNamedFunction(3, 5)
```

---

2. What's the value of `result`?

```js
const badlyNamedFunction = (a, b = 3) => a + b

const result = badlyNamedFunction(4)
```

---

3. Write a function `sumOfDoubles` that takes 3 parameter, doubles each and returns their sum.

---

4. What will be logged?

```js
const data = { name: 'Henning', role: 'Engineer' }

console.log(`${data.name}'s role is ${data.role}`)
```

---

5. Write a function `greet` that takes a name and returns a greeting. Make use of template literals and arrow functions.

---

6. What will be logged?

```js
const person = { name: 'Henning', age: 28 }
const person2 = person
person2.name = 'Nina'

console.log(`Hello, ${person.name}`)
```

---
