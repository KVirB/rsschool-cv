# VIKTOR BORODULIN

## Frontend Developer

### Contacts:

**Phone:** +375 (29) 295-58-97 <br>
[GitHub](https://github.com/KVirB) <br>
[CodeWars](https://www.codewars.com/users/KVirB) <br>
[VKontakte](https://vk.com/kvirb) <br>

---

### About Myself:

I am 24 years old, i graduated from Vitebsk State Technological University, and i`am currently working there as a frontend developer. <br>
I don't want to stop there, so I came to the courses to raise skills in this area. <br>

> Knowledge and understanding are ambiguous.

---

### Skills:

- HTML
- CSS
- JAVASCRIPT
- REACT + REDUX
- GIT
- SQL

### Code example:

**You will be given an array of numbers. You have to sort the odd numbers in ascending order while leaving the even numbers at their original positions.**

```javascript
function sortArray(array) {
  let index = [];
  let nechet = [];
  array.map((i, n) => (i % 2 === 0 ? "" : (nechet.push(i), index.push(n))));
  nechet.sort((a, b) => a - b);
  for (let i = 0; i < nechet.length; i++) {
    array[index[i]] = nechet[i];
  }
  return array;
}
```

---

### Education:

- Vitebsk State Technological University (completed)
- [LearnJavascript](https://learn.javascript.ru/) (completed)
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

### Languages:

- Ruussian - Native
- English - B1
