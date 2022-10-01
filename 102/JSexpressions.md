# Expressions and Operators

At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

All complex expressions are joined by operators, such as = and +
**Loops and iteration**

Loops offer a quick and easy way to do something repeatedly. You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times.

A for statement looks as follows:

     for (initialExpression; conditionExpression; incrementExpression) {
         // code block to be executed -statement
     }

     Example:

    for (let i = 0; i < 5; i++) {
    text += "The number is " + i + "<br>";
    }
From the example above, you can read:

Expression 1 sets a variable before the loop starts (let i = 0).

Expression 2 defines the condition for the loop to run (i must be less than 5).

Expression 3 increases a value (i++) each time the code block in the loop has been executed.

## Resources

* [MDN Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
* [Functions](https://www.w3schools.com/js/js_functions.asp)
* [Operators](https://www.w3schools.com/js/js_operators.asp)
* [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

[Back to Home Page](../README.md)
