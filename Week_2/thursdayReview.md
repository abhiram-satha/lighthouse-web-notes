# Objects

* function inside an Object is called a method  


<br>  


# const , let, var

Const  

* block scope

Let
* ```javascript
  function start () {
    for (let i = 0; i < 3; i++) {
      console.log(i); // => prints 0, 1, 2
    }
    console.log(i); // => undefined; i is not defined error message
  }
  ```
* block scope

Var  
* the scope is not limited to the code block but the function
* ```javascript
  function start () {
    for (var i = 0; i < 3; i++) {
      console.log(i); // => prints 0, 1, 2
    }
    console.log(i); // => print 3, i will print 3 because var is not limited to code block but the function start 
  }
  ```
* not to be used anymore 