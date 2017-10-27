# Destructuring

## Tablice

Przypisać wartości do zmiennych `error` i `ok` przy pomocy `destructuring`.

```javascript
let colors = ['red', 'green'];
let error = colors[0];
let ok = colors[1];
```

## Obiekty

Przypisać wartości do zmiennych `name` i `email` przy pomocy `destructuring`.

```javascript
var user = { 
  name: 'Bob', 
  email: 'bob@gmail.com',
  age : 43
};

????
console.log(`My name is ${name}, my email is ${email}`);
```

Przypisać bezpośrednio do stałych `width` i `height` wynik funkcji `dimensions`.

```javascript
const dimensions = () => ({ width: 100, height: 200 });

```


### Więcej
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment