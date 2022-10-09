# Imutabilidade 

- Uma variável não vai variar
- Se você precisar mudar uma variável, você não muda, você cria uma nova

```js

// exemplo em JS
const cart = {
  quantity: 2, 
  total: 200
}

// não pode
cart.quantity = 3

// como tem que fazer:
const newCart = {...cart, quantity: 3}


// exemplo em ReactJS
const = [amount, setAmount] = useState(0)

//não pode
amount = 2


// como deve fazer:
setAmount(2)

```