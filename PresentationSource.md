<section data-markdown>

## Overview of Programming
Programming is basically

- Types
- Variables
- Lists
- Objects
- Functions
- Loops
- Control Flow
- Expressions

</section> <section data-markdown>

### Variables
A variable is a named place where you can store information you can use later

## Example
Storing numbers for addition

</section> <section data-markdown>

## Demonstration

</section> <section data-markdown>

### Arrays (Lists)
An ordered list of data that can be accessed by index. Index starts at zero.

## Example
List of users; Temperatures for the week

    var users = ["Bob", "Lisa", "Aaron"];
    alert(users[0])
    // => alerts "Bob"

</section> <section data-markdown>

## Demonstration

</section> <section data-markdown>

### Objects (Hashes, Dictionaries)
A data structure based on keys and values. Keys must be strings but values can be any of the other Types.

## Example
Any complex data structure.

- state of game
- users
- data returned from external service e.g. Twitter, Weather

    var bob = { firstName: "Bob", lastName: "Smith", phone: "333444343"};
    alert(bob.firstName);
    // => alerts 'Bob'

</section> <section data-markdown>

## Demonstration

</section> <section data-markdown>

### Functions
A piece of code that performs a task

## Example
Adding two numbers together; Trahsforming a list of data.

    function addTwo (n) {
      alert(n + 2)
    }
    addTwo(4);
    // => alerts 6

or return a value

    function addTwo (n) {
      return n + 2;
    }
    var newValue = addTwo(4);
    alert(newValue);
    // => alerts 6

</section> <section data-markdown>

## Demonstration

</section> <section data-markdown>

### Loops
A variable is a named place where you can store information you can use later

</section> <section data-markdown>

### for
takes as arguments

1. Initial value
2. It will keep looping until this evalutes to false
3. What to change (increment or decrement the counter)

</section> <section data-markdown>

### Example

    for (var i = 0; i < 10; i += 1) {
      alert(i);
    }

</section> <section data-markdown>

### while

</section> <section data-markdown>

### Example
Storing numbers for addition

</section> <section data-markdown>

## Demonstration

</section> <section data-markdown>

### Control Flow
Your code making decisions

</section> <section data-markdown>

### if/else
If this is true, then do something, otherwise do something else

## Example
Act on received data, only if you really received data

    var n = 4;
    if (n === 3) {
      alert("there is a problem here");
    } else {
      alert("At least it doesn't equal 3"
    }
</section> <section data-markdown>

## Demonstration

</section> <section data-markdown>

## Hello World example

    // save the "Hello World!" string in a variable named 'hello'
    var hello = "Hello World!";

    // built in JavaScript 'alert' pops up dialog in browser with it's argument
    alert(hello);

</section> <section data-markdown>

## JavaScript Documentation
### Mozilla (Firefox) Javascript Developer Docs
https://developer.mozilla.org/en/docs/JavaScript
### Or in Spanish!
https://developer.mozilla.org/__es__/docs/JavaScript
</section>
