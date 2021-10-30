# Saturday Class => Functions  

### Parameter
* When you create a function, what is in the parameter is a parameter
### Argument
* Data that is being passed when you are calling a function


```javascript 
function add (a , b) {  //a , b are parameters
  return a + b
}

add(2,2) // 2 ,2 are arguments
```   



<strong>Function declaration </strong>
* this type of function declaration will be hoisted to the top 
```javascript
function printUserName() {}
```
<strong>Function Expression</strong>

```javascript
const printUserName = function() {}
```

<strong> Anonymous Function </strong> (any function that does not have a name, Function Express is a form of anonymous function since is has no name) 
* must be given a variable or passed as an argument to invoke this function
```javascript
function () {}
```

```javasctipt
(function() {
  console.log("Hello World")
} )();
```

Arrow Function
* would get the label assigned and would not be an anonymous function
```javascript
const printUserName = () => {

} 
```   
Arrow functions has its own this and does not come from the parents object; and can not be used to create objects; this in an Arrow function references the function itself

//Function by reference (look into it)  

<br>

### First Class Citizens Functions

* Functions in Javascript are FIRST CLASS CITIZENS  
<br>


### Higher Order Functions
* A function that accepts another function as an input parameter or return another function  
* Example of Array Higher Order Functions: 
  * .map
  * .reduce
  * .filter
  * .ForEach
  * .some
  * .every  
  

    
  <br>

### Single Responsibility Principle
* having a function do only one specific action

