### About me: https://www.linkedin.com/in/heribertoroman/ 
The Coding Workstations are comprised of small repetitive coding prompts derived from the ideology/pedagogy of the [cThink](https://github.com/getromandev/cThink) platform. The goal is to provide students with visual, audio, and kinesthetic learning types, an opportunity to get their hands dirty and acquire a level of competency with lite Computer Science & Javascript fundamentals.

1. Clone this repo to your local machine and work on the solutions
```or```
2. Work on the solutions via **Codepen** https://codepen.io/getromandev/pen/gOOjZpW

## Complete Each Mini Prompt
### Arrays
____________________________________________________________________________________
##### ```Create 3 empty arrays```

*  One array should hold `4 strings` of your choice
*  One array should hold `3 numbers` of your choice
*  One array should hold `1 boolean` value

### Array Methods
____________________________________________________________________________________

*  Select your `string array` and `add` a new string element at the end of the array using an array method of your choice
*  Select your `string array` and `remove` the last element using an array method  
*  Select your `string array` and `remove` the `first element` of the array
*  Select your `number array` and `remove` the `first two` elements in the array
*  Select your `number array` and `add` two new numbers
*  Select your `number array` and `sort` the array in `ascending` order
*  Select your `number array` and replace the `first two` elements with `two different` numbers
*  Select your `boolean array` and find the `length` of the array

### Looping Through Arrays 1
____________________________________________________________________________________
##### ```Create a function called loopThroughArray(){}```
*  In the function create `3` for loops
 *  one that `loops` through your `string array`
 *  one that `loops` through your `number array`
 *  one that `loops` through your `boolean array`
* In each for loop `console.log()` each element and its primitive data type

### Looping Through Arrays 2
____________________________________________________________________________________
*  Create a 4th `array` that holds 3 `strings`, 4 `numbers`, 2 `boolean` values.
*  Create a new `variable` called `stringDataType` and assign it an empty `array`.
*  Create a new `variable` called `numberDataType` and assign it an empty `array`.
*  Create a new `variable` called `booleanDataType` and assign it an empty `array`.

##### ```Create a function called findTypeOf(){}```

*  Loop through the 4th `array` you just created
* Write a conditional that checks every index primitive data type 
  * `if` the data type is a `string` then `push` it to the `stringDataType array`
  * `if` the data type is a `number` then `push` it to the `numberDataType array`
  * `if` the data type is a `boolean` then push it to the `booleanDataType array`
* return the `data type` with the `most instances`

### Objects Example
____________________________________________________________________________________
Objects are similar to arrays, except that instead of using indexes to access and modify their data, you access the data in objects through what are called properties.

Objects are useful for storing data in a structured way, and can represent real world objects, like a car.

Here's a sample car object without properties:
```let car = {};```

Here's a sample car object with properties:
```
let car = {  
  make: 'Honda',  
  model: 'Accord',  
  numberOfTires: 4,  
  competitors: ['Ford', 'Chevy', 'Nissan'],
  isCarRegistered: false,
  location: 'New York',
  giveMeInfoAboutMyCar: function() {
    return `I have a ${this.make} ${this.model} and my car is registered: ${this.isCarRegistered}, and our number one competitor is: ${this.competitors[2]}`
    } 
}
```

Here is an example of calling the `giveMeInfoAboutMyCar` method that lives in my car object `console.log(car.giveMeInfoAboutMyCar())`.

### Objects
____________________________________________________________________________________
*  Create an Object literal
*  Store your object in a `variable` called `ford`
*  Take your ford Object and add `5 properties` that hold
 *  a key: `make` and a value: `string` 
 *  a key: `numberOfTires`  and a value: of an `integer`
 *  a key: `competitors` and a value: of an `array` that holds `3 strings elements`
 *  a key: `isCarRegistered` and a value: of a `boolean`
 *  a key: `myMethod` and a value: that holds a `method` that `console.logs()` details about your object  i.e.
     *  "I have a `make` `model` and my car is registered: `boolean`, and our number one competitor is: `choose any competitor that is currently sitting in your array`"

*  Call the `myMethod` that is sitting in your ford object If you completed this correctly you should see a string with your message in the console. 👍