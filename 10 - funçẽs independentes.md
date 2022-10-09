# Funções independentes

• Só trabalha com dados que foram passados dentro dela

• Deverá ter ao menos 1 argumento

• Deverá retornar algo

• Nada que acontecer lá dentro afeta o mundo externo
    • dados imutáveis
    • não guardar estado (stateless)

• Não faremos uso de loops (for, while), mas se houver necessidade de tal, usaremos recursão (a função chama ela mesma)

# ex.:

```js
const random = (number, Math) => 
  Math.floor(Math.random() * number);

// recursive
// Find the factorial of a number
const factorial = x => {
  // if number is 0
  if (x === 0) {
    return 1;
  }

return x * factorial(x - 1);

```