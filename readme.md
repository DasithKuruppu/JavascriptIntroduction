# Introduction to javascript/typescript

### What is JavaScript ?

JavaScript is a cross-platform, object-oriented scripting language used to make webpages interactive (e.g. having complex animations, clickable buttons, popup menus, etc.).

### What kind of language is it ?

It is Dynamic language, All variables are dynamic (both in type and existance), and even the code is dynamic. You can create new variables at runtime, and the type of variables is determined at runtime. You can create new functions at any time, or replace existing functions. When used in a browser, code is added when more script files are loaded, and you can load more files any time you like.

### What does it run on and how is it executed ?

A JavaScript engine is a computer program that executes JavaScript (JS) code. The first JS engines were mere interpreters, but all relevant modern engines utilize just-in-time compilation for improved performance.
JS engines are developed by web browser vendors, and every major browser has one.

### What is Javascript used for ?

Primarily for Client side web scripts , web applications etc.
For server side.
For desktop application development.
For native / mobile application development.
Also in IOT http://johnny-five.io/ etc.

### Latest major change to javascript ?  
* ECMAScript 5 http://speakingjs.com/es5/ch25.html
* ECMAScript 6 http://es6-features.org/#Constants
* ECMAScript 7+ https://derickbailey.com/2017/06/06/3-features-of-es7-and-beyond-that-you-should-be-using-now/

### Typescript

TypeScript is a superset of JavaScript which primarily provides optional static typing, classes and interfaces. One of the big benefits is to enable IDEs to provide a richer environment for spotting common errors as you type the code.
http://www.typescriptlang.org/play/

### Javascript basic variable types

1. **String** -	A sequence of text known as a string. To signify that the value is a string, you must enclose it in quote marks.	var     myVariable = 'Bob' or var myVariable = "Bob";
2. **Number** -	A number. Numbers don't have quotes around them.	var myVariable = 10;
3. **Boolean** -	A True/False value. The words true and false are special keywords in JS, and don't need quotes.	var myVariable = true;
4. **Array**	A structure that allows you to store multiple values in one single reference.	var myVariable = [1,'Bob','Steve',10];
Refer to each member of the array like this:
myVariable[0], myVariable[1], etc.
5. **Object** -	Basically, anything. Everything in JavaScript is an object, and can be stored in a variable. Keep this in mind as you learn.	var myVariable = document.querySelector('h1');
All of the above examples too.

### Ways of declaring variables (var,let,const)

### Hello world !

* Output data either to console or dom.

### Operators 
```
1 == 1; 
1 == '1';
'1' == 1;
'foo' == 'foo'; 
[1,2,3] == [1,2,3];

```
https://github.com/denysdovhan/wtfjs#-is-equal-

### Functions

* declare function
* arguments to a function
* returning from a function

### Arrays and data structures.

* Initializing array
* Adding to an array
* Deleting from array

### Classes

``` 
function User(name) {
  this.name = name;
}

User.prototype.sayHi = function() {
  alert(this.name);
}

let user = new User("John");
user.sayHi();

```


```
class User {

  constructor(name) {
    this.name = name;
  }

  sayHi() {
    alert(this.name);
  }

}

let user = new User("John");
user.sayHi();

```


### footnotes

https://books.google.lk/books?id=l8dcCgAAQBAJ&pg=PA35&lpg=PA35&dq=the+joy+of+javascript+is+rooted+in+its&source=bl&ots=gNxX1wCwG5&sig=ACfU3U3K745e2MdTb93xC_o4LIMwaLhEzg&hl=en&sa=X&ved=2ahUKEwjglfGn7-7gAhXhmeYKHaZjAL8Q6AEwAHoECAgQAQ#v=onepage&q=the%20joy%20of%20javascript%20is%20rooted%20in%20its&f=false



