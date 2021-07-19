### Задание для погружения в TypeScript

- Выкачать и развернуть проект https://github.com/vasiliy-uskov/typescript_template
- Реализовать консольное приложение, которое на вход принимает список строк, на выход количество строк палиндромов.

Для чтения из консоли использовать встроенный модуль readLine
```javascript
import {createInterface} from "readline"

createInterface({
    input: process.stdin,
    output: process.stdout,
}).on('line', line => {
    console.log('You just print a line', line)
})
```

Так же познакомьтесь с фишками стандарта [ES6](https://habr.com/ru/post/305900/)
