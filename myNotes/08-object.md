## Object

object let us group multiple values together:

```javascript
const product = {
  name: 'socket',
  price: 30
}

console.log(product);

```

change the value of a property:

```javascript
product.price = 50;
console.log(product);
```

Sou that how the object works:
  - we group multiple values together 
  - we can change the value of a property on the left side

To create a new property we can use dot notation:
```javascript
product.newProperty = true;
```

To delete a property we can use dot notation:
```javascript
delete product.newProperty;
```

Why we use object
- make out code more organized
- let us group multiple values together
- let us use multiple values together

