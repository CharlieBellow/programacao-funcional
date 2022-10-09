# Stateless

- Não guarda estado

- A função só conhece dados entregues a ela

- A resposta não poderá variar

```js

let number = 2;

// stateful function
function square() { return number * number }

number = square() // aqui o resultado seria retornado cm 4

// isso faz com que eu nunca saiba o que vai retornar, então ela guarda um estado

// stateless function 
const square = n => n* n; // aqui o que vi ser retornado sempre vai ser o que que colocar. se eu colocar 2 vai ser retornado o resultado de 2*2

//por isso não é interessante guardar dados dentro da função. 

```