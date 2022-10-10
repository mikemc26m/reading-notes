# 201 - Problem Domain, Objects and the DOM

## [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. How would you describe an object to a non-technical friend you grew up with? A collection of data that includes functions, variables and code.

2. What are some advantages to creating object literals? Makes it easier to transfer a series of related and structured items, like into a server database.

3. How do objects differ from arrays?

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

    * In an object method, `this` refers to the object.
    * Alone, `this` refers to the global object.
    * In a function, `this` refers to the global object.
    * In a function, in strict mode, `this` is undefined.
    * In an event, `this` refers to the element that received the event. 
    * [resource](https://www.w3schools.com/js/js_this.asp)

          >const dog = {
          name: 'Spot',
          age: 2,
          color: 'white with black spots',
          humanAge: function (){
          console.log(`${this.name} is ${this.age*7} in human years`);
          }
          }

### [Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1. What is the DOM? Document Object Model is data representation of the objects that comprise the structure and content of a web document.

2. Briefly describe the relationship between the DOM and JavaScript. JavaScript is code, the DOM is used to access docuents and elements.

## Bookmark and Review

[Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

[What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

[Return to Home Page](../README.md)
