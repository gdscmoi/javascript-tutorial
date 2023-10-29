

# Variables In JavaScript


We can easily describe variables as containers for storing data.

There are several ways through which we can define variables in javascript; either automatically or by using the var, let or const keywords.

Let us have a look at some examples:

## Automatic Declaration
In this case, the variables will get declared as variables automatically:


```bash
  //Creating a variable named x and storing the value 20 in it
  x=20;

  //creating a variable named y and storing the value 30 in it
  y=30;

  //creating the variable z and storing the sum of variable x and variable y in it
  z=x+y;
```
## Declaration using the var keyword 

In this case we are using the var keyword 

```bash
  //Creating a variable named myAge using the var keyword and storing the value 27 in it

  var myAge=27;
```

## Declaration using the let keyword

```bash
  //Creating a variable named herAge using the let keyword and storing the value 25 in it

  let herAge=25;
```
## Declaration using the const keyword

```bash
  //Creating a variable named myAge, herAge and OurTotalAge and storing the sum of variable herAge and myAge in the variable OurTotalAge 
  
    const herAge=25;
    const myAge=27;
    const OurTotalAge=herAge+myAge;

```

# JS Variables

In JavaScript, we can declare varible using three different keywords:
* var : create a variable globally availale throught the program
* let : create a variable available just the block of code declared, as if statement or function
* const : create a read-only reference to a value. 

Create a variabole called carName and assign the value Volvo to it.
```
var carName = "Volvo";
```
Create a variable called X, assign the value 50 to it:
```
var x  = 50;
```
Display the sum of 5+10, using the varuable: x and y
```
var x = 5;
var y = 10;
document.gtElementById("demo").innerHTML = x + y;
```
Create a varialbe called Z, assign x+y to it, and display the result in an alert box
```
var x  = 5;
var y = 10;
var z = x + y;
alert(z);
```
On one sigle line, declare threee variable with the following names and values:
* firstName = "John"
* lastName = "Doe"
* age = 35
```
var firstName = "John" ,  lastName = "Doe" , age = 35;
```

# JS Operators

* ```typeof(x)``` : returns the Datatype of the parameter x
* ```new```       : Keyword that allows to create an instance of an Object or builtin Datatype (ex: String)

## typeof
```
// Will print out : Number
Console.log(typeof(45));

// Will print out : Boolean
Console.log(typeof(true));
```
 ## new
```
function person(name , surname, age)
{
  this.name = name;
  this.surname = surname;
  this.age = age; 
}

const person1 = new person('Davide' , 'Pollicino' , 20);
// Output: 20
console.log(person1.age);
```


Multiply 10 with 5, and alert the result:
```
alert(10*5);
```
Divide 10 by 2, and alert the result:
```
alert(10/2);
```
Alert the remainder when 15 is divided by 9:
```
alert(15%9);
```
Use the assignment operator that will result in x being 15 (same as x = x + y )
```
x = 10;
y = 5;
x += y;
```
Use the correct assignment operator that will result in X being 50 (same as X = X * Y);
```
x = 10;
y = 5;
x *= y;
```

