// Function Declaration

```js
function add(a, b) {
    return a + b;
}
```

// Arrow Function (Shorthand)
```js
const multiply = (a, b) => a * b;
```

// Default Parameters
```js
const welcome = (name = "Guest") => `Welcome ${name}`;
```

Asynchronous JavaScript
Handling operations that take time (like API calls).

// Promises

```js
const fetchData = () => {
    return new Promise((resolve, reject) => {
        const success = true;
        success ? resolve("Data received") : reject("Error");
    });
};
```

// Async/Await (Modern Standard)
```js
async function getResult() {
    try {
        const data = await fetchData();
        console.log(data);
    } catch (err) {
        console.error(err);
    }
}
```
