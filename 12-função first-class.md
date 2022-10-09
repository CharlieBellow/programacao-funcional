# First-class function

• Podem estar em 1qualquer lugar, inclusive, como parâmetro outras funções

• A função poderá entendida como uma variável

```js
const sayMyName = () => console.log('Mayk')
const runFunction = fn fn() // função sendo passada como variável

runFunction (sayMyName) //fução passada como referência
runFunction(() => console.log('discover')) //função sendo passada como parâmetro

console.log(runFunction(Math.random)) // função passada como referência

```