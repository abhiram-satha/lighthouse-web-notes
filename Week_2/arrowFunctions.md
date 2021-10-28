# Arrow Functions

```javascript

// BEFORE: anonymous callback as function expression 
[1,2,3].forEach(function (num) {
  console.log('num: ', num);
});

// AFTER: anonymous callback as arrow function
[1,2,3].forEach((num) => {
  console.log('num: ', num);
});

// FURTHER: Creating as a one-liner
[1,2,3].forEach(num => console.log('num: ', num));

```
**Arrow Functions don't get assigned a value for this** but traditional functions would  
<br>

### Benefits of Arrow Function
* small
* inline
* single-purpose 