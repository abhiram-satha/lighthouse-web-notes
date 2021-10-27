# Tuesday Lecture


Primitive Data Types: (can not be mutated but can be reassigned and are stored in memory)
* Strings
* Booleans
* Numbers (includes integars and floating numbers)
* undefined
* null
* Symbols (not as commonly used)
  const type = Symbol('a'); // strings that will never use its value (it will always be unique)

* BigInt (not as commonly used) (maximum number that is considered an integar, greater than that is a BigInt) Number.MAX_SAFE_INTEGER to access the biggest number allowed in JS before it becomes a BigInt
  const bigint = 98765432n

Non-Primitive Data Types (data structures)
* Arrays
* Objects (key (will always be strings) , value pair)
 
* Function

<br>

### [Python Tutor](www.pythontutor.com)   => website to see if data is stored in memory or not 

<br>
## Objects

 * use Dot Notation or Bracket Notation allows you to access dynamic like if you pass it as a variable (bracket notation is more flexible)
 
### Delete a Key / Value Pair

```javascript

delete key.value;

OR 

object.key = null; 

```

## Iterables
Arrays: for | for of | for each
<br>
Objects: for in

