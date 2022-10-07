# 201 - HTML Lists, Control Flow with JS and CSS Box Model

## Reading

### [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) and [Unordered lists.](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

1. When should you use an unordered list in your HTML document?

    When you want to group a collection of items that don't have a necessary order.

2. How do you change the bullet style of unordered list items?

    By using CSS `list-style`

3. When should you use an ordered list vs an unorder list in your HTML document?

    When the list should be numbered due to the meaningfulness of the items.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

    By using `list-style` and CSS counters

## [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

### [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

    "Hey Margin, thanks for protecting the box from the outside", says Padding. "No problem Padding", says Margin, "you take care of that padded space between the content and the border.

2. List and describe the four parts of an HTML elements box as referred to by the box model.

      * Content Box - area where the content is displayed
      * Padding Box - padding sits around the content
      * Border Box - wraps the content and padding
      * Margin Box - outermost layer, wraps everything

## [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

### [Arrays.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays) [Operators and Expressions.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators) [Conditionals.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals) [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

1. What `data types` can you store inside of an `Array`?

    Variable data lists. Strings, numbers, objects and other arrays.

2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why? Yes it is valid. By using brackets. `console.log(arrayName[0])`

    > const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

3. List five shorthand operators for assignment in javascript and describe what they do.
    * = assignment
    * += addition assignment
    * -= subtraction
    * *= multiplication
    * /= division

4. Read the code below and evaluate the last expression and explain what the result would be and why. I believe 10 + false = 10 + dog should be 10dog.

    > let a = 10;
 let b = 'dog';
 let c = false;
 // evaluate this
 (a + c) + b;

5. Describe a real world example of when a conditional statement should be used in a JavaScript program. When an input value should equal another value.

6. Give an example of when a Loop is useful in JavaScript. If asking a question and looking for a correct answer. The user may be prompted to answer the question again.

Resources

* [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) and [Unordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) lists
* [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
* [CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
* [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
* [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays), [Operaters an Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators), [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals), [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

[Return to Home Page](../README.md)
