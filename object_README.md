# Writing an Object in javaScrpt

![Computer](https://media.istockphoto.com/id/1451309507/photo/closeup-of-young-asian-woman-software-developers-using-computer-to-write-code-sitting-at-desk.webp?b=1&s=170667a&w=0&k=20&c=nEH-Salw563oWFvIV3YBDWlFjpql9d5iaSTEm8HWsV4=)



An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life

## Basic syntax
```javascript
const objectName = {
    property1: value1,
    property2: value2,
    },
```
**Object Definition**: An object is defined using curly braces {} and can contain properties and methods.

**Properties**: These are key-value pairs that describe the characteristics of the object.

**Values**: These can be any data type, including strings, numbers, arrays, functions (methods), other objects, etc.

*Example*:
```javascript
{firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```

Creating Empty object and Adding properties

*Example*:
```javascript
const person = {};

// Add Properties
person.firstName = "John";
person.lastName = "Doe";
person.age = 50;
person.eyeColor = "blue";
```
> Decleration:
Create an empty JavaScript object using {}, and add 4 properties

## Objects and functions
* Sometimes we need to create many objects of the same type.

* To create an object type we use an object constructor function.

* It is considered good practice to name constructor functions with an upper-case first letter.

*Example*
```javascript
function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}
```

For more information on functions and how they are used in JS, check out the 
[W3Scools]( https://www.w3schools.com/js/js_object_definition.asp).