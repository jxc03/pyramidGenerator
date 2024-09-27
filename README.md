# pyramidGenerator
Free Code Camp - Responsive Web Design - Learn introductory JavaScript by building a pyramid generator

## **Step 1** 
JavaScript is the programming language that powers the web. Unlike the HTML and CSS you have learned previously, JavaScript is most commonly used to write logic instead of markup.<br>
One of the most important concepts in programming is variables. A <i>variable</i> points to a specific memory address that stores a value. Variables are given a name which can be used throughout your code to access that value.<br>
Declaring a variable means giving it a name. In JavaScript, this is often done with the `let` keyword. For example, here is how you would declare a `hello` variable:<br>
`let hello;`<br>
Variable naming follows specific rules: names can include letters, numbers, dollar signs, and underscores, but cannot contain spaces and must not begin with a number.<br>
Declare a `character` variable in your code.<br>
<i>Note</i>: It is common practice to end statements in JavaScript with a semicolon. `;`

```js
let character;
```

## **Step 2** `
Your `character` variable currently does not have a value. You can assign a value using the assignment operator `=`. For example:<br>
`let hello = "Hello";`<br>
Assigning a value to a variable at the moment of its declaration is known as <i>initialization</i>.<br>
Initialize your `character` variable by assigning it the value `"Hello"` during its declaration.

```js
let character = "Hello";
```

## **Step 3** 
JavaScript has seven primitive data types, with `String` being one of them. In JavaScript, a <i>string</i> represents a sequence of characters and can be enclosed in either single (`'`) or double (`"`) quotes.<br>
Note that strings are <i>immutable</i>, which means once they are created, they cannot be changed.<br>
Change your `"Hello"` string to use single quotes.

```js
let character = 'Hello';
```

## **Step 4** 
The <i>console</i> allows you to print and view JavaScript output. You can send information to the console using `console.log()`. For example, this code will print `"Naomi"` to the console:<br>
`let developer = "Naomi";`<br>
`console.log(developer);`<br>
The code above accesses the `developer` variable with its name in the `console.log()`. Note that the value between the parentheses is the value that will be printed.<br>
Print the value of the `character` variable to the console. Then, click the "Console" button to view the JavaScript console.

```js
console.log(character);
```

## **Step 5** 
When a variable is declared with the `let` keyword, you can <i>reassign</i> (or change the value of) that variable later on. In this example, the value of `programmer` is changed from `"Naomi"` to `"CamperChan"`.<br>
`let programmer = "Naomi";`<br>
`programmer = "CamperChan";`<br>
Note that when reassigning a variable that has already been declared, you do <b>not</b> use the `let` keyword.<br>
After your `console.log`, assign the value `"World"` to your `character` variable.

```js
character = "World";
```

## **Step 6** 
Now log your `character` variable to the console again. You should see the string `"Hello"`, then the string `"World"`, in the console.

```js
console.log(character);
```

## **Step 7** 
When variable names are more than one word, there are specific naming conventions for how you capitalize the words. In JavaScript, the convention to use is <i>camel</i> case.<br>
Camel case means that the first word in the name is entirely lowercase, but the following words are all title-cased. Here are some examples of camel case:<br>
`let variableOne;`<br<>
`let secondVariable;`<br>
`let yetAnotherVariable;`<br>
`let thisIsAnAbsurdlyLongName;`<br>
Use camel case to declare a new `secondCharacter` variable.

```js
let secondCharacter;
```

## **Step 8** 
When you declare a variable without initializing it, it is considered <i>uninitialized</i>. Currently, your `secondCharacter` variable is uninitialized.<br>
Add a `console.log()` to see what the value of your `secondCharacter` variable is.

```js
console.log(secondCharacter);
```

## **Step 9** 
The default value of an uninitialized variable is `undefined`. This is a special data type that represents a value that does not have a definition yet.<br>
You can still assign a value to an uninitialized variable. Here is an example:<br>
`let uninitialized;`<br>
`uninitialized = "assigned";`<br>
Assign the string `"Test"` to your `secondCharacter` variable below your declaration. Open the console to see how your log has changed.

```js
secondCharacter = "Test";
```

## **Step 10** 
You can also assign the value of a variable to another variable. For example:<br>
`let first = "One";`<br>
`let second = "Two";`<br>
`second = first;`<br>
The `second` variable would now have the value `"One"`.<br>
To see this in action, change your `secondCharacter` assignment from `"Test"` to your `character` variable.<br>
Then open the console to see what gets logged.

```js
secondCharacter = character;
```

## **Step 11** 
You are now ready to declare your next variable. Remove both `console.log` statements, and the `character` reassignment.<br>
Also remove your `secondCharacter` variable, but leave the `character` initialization unchanged.

```js
```

## **Step 12** 
Use `let` to declare a `count` variable. Assign it the <i>number</i> `8`. When using a number value, you do not use quotes. For example:<br>
`let money = 100;`

```js
let count = 8;
```

## **Step 13** 
With the `number` data type, you can perform mathematical operations, like addition. Try printing `count + 1` to the console.

```js
console.log(count + 1);
```

## **Step 14** 
You can also perform subtraction (`-`), multiplication (`*`), and division (`/`). Feel free to experiment with the operators and numbers in your `console.log`. When you are ready to move on, remove the `console.log`.

```js
```

## **Step 15** 
In programming, you will often need to work with lots of data. There are many data structures that can help you organize and manage your data. One of the most basic data structures is an <i>array</i>.<br>
An <i>array</i> is a non-primitive data type that can hold a series of values. Non-primitive data types differ from primitive data types in that they can hold more complex data. Primitive data types like strings and numbers can only hold one value at a time.<br>
Arrays are denoted using square brackets (`[]`)`. Here is an example of a variable with the value of an empty array:<br>
`let array = [];`
Declare a `rows` variable and assign it an empty array.

```js
let rows = [];
```

## **Step 16** 
When an array holds values, or <i>elements</i>, those values are separated by commas. Here is an array that holds two strings:<br>
`let array = ["first", "second"];`<br>
Change your `rows` declaration to be an array with the strings `"Naomi"`, `"Quincy"`, and `"CamperChan".` The order of values in an array is important, so follow that order. Remember that strings are case-sensitive.

```js
let rows = ["Naomi", "Quincy", "CamperChan"];
```

## **Step 17** 
You can access the values inside an array using the <i>index</i> of the value. An index is a number representing the position of the value in the array, starting from `0` for the first value.<br>
You can access the value using <i>bracket notation</i>, such as `array[0]`.<br>
Use `console.log` and bracket notation to print the first value in your `rows` array.

```js
console.log(rows[0]);
```

## **Step 18** 
Arrays are special in that they are considered <i>mutable</i>. This means you can change the value at an index directly.<br>
For example, this code would assign the number `25` to the second element in the array:<br>
`let array = [1, 2, 3];`<br>
`array[1] = 25;`<br>
Update the <b>third</b> element of your `rows` array to be the number `10`. Then print the `rows` array to your console.

```js
rows[2] = 10;
console.log(rows);
```

## **Step 19** 
Notice how the value inside your `rows` array has been changed directly? This is called <i>mutation</i>. As you learn more about arrays, you will learn when to mutate an array, and when you should not.<br>
Before moving on, this is a great opportunity to learn a common array use. Currently, your code accesses the last element in the array with `rows[2]`. But you may not know how many elements are in an array when you want the last one.<br>
You can make use of the `.length` property of an array - this returns the number of elements in the array. To get the last element of any array, you can use the following syntax<br>
`array[array.length - 1]`<br>
`array.length` returns the number of elements in the array. By subtracting `1`, you get the index of the last element in the array. You can apply this same concept to your `rows` array.<br>
Update your `rows[2]` to dynamically access the last element in the `rows` array. Refer to the example above to help you.<br>
You should not see anything change in your console.

```js
rows[rows.length - 1] = 10;
```

## **Step 20** 
For now, remove your first console log and your `rows[2]` assignment. Leave the second `rows` log statement for later.

```js
```

## **Step 21** 
A <i>method</i> in JavaScript is a function that's associated with certain values or objects. An example you've already encountered is the `.log()` method, which is part of the `console` object.<br>
Arrays have their own methods, and the first you will explore is the `.push()` method. This allows you to "push" a value to the end of an array. Here is an example to add the number `12` to the end of an array:<br>
`array.push(12);`<br>
Use `.push()` to add the string `"freeCodeCamp"` to the end of your `rows` array. Add this code before your `console.log` so you can see the change you made to your array.

```js
rows.push("freeCodeCamp");
```

## **Step 22** 
Another method essential for this project is the `.pop()` method. It removes the last element from an array and <i>returns</i> that element.<br>
When a method returns a value, you can think of it as giving the value back to you, making it available for use in other parts of your code.<br>
Declare a `popped` variable, and assign it the result of `rows.pop()`. Then, log your `popped` variable.

```js
let popped = rows.pop();
console.log(popped);
```

## **Step 23** 
You should have seen `"freeCodeCamp" ` printed to the console. This is because `.pop()` returns the value that was removed from the array - and you pushed `"freeCodeCamp"` to the end of the array earlier.<br>
But what does `.push()` return? Assign your existing `rows.push()` to a new `pushed` variable, and log it.

```js
let pushed = rows.push("freeCodeCamp");
console.log(pushed);
```

## **Step 24** 
Were you expecting to see `4 `in the console? `.push()` returns the new length of the array, after adding the value you give it.<br>
It is important to be aware of what values a method returns. Take some time to experiment with `.push()` and `.pop()`. When you are ready, remove all of your .`push()` and `.pop()` calls, and your `console.log` statements.

```js
```

## **Step 25** 
Change your `rows` declaration to be assigned an empty array again.<br>
Also, change your `'Hello'` string to use double quotes again. Generally, it does not matter which of the two you prefer, but you will want to be consistent in that choice throughout your project.

```js
let character = "Hello";
let rows = [];
```

## **Step 26** 
The `let` keyword allows a variable to be reassigned. This means you could change `character` later to be a completely different value.<br>
For this project, you will not want to change these variable values. So instead, you should use `const` to declare them. `const` variables are special.<br>
First, a `const` variable cannot be reassigned like a `let` variable. This code would throw an error:<br>
`const firstName = "Naomi";`<br>
`firstName = "Jessica";`<br>
A `const` variable also cannot be uninitialized. This code would throw an error:<br>
`const firstName;`<br>
Replace your `let` keywords with `const`.

```js
const character = "Hello";
const count = 8;
const rows = [];
```

## **Step 27** 
You are now ready to start building your pyramid generator. Your `character` variable will serve as the building block for the pyramid.<br>
`"Hello"` might not work very well for that. Change the value of `character` to be the hash character `"#"`.

```js
const character = "#";
```

## **Step 28** 
To generate a pyramid, you will need to create multiple rows. When you have to perform a task repeatedly until a condition is met, you will use a <i>loop</i>. There are many ways to write a loop.<br>
You are going to start with a basic `for` loop. `for` loops use the following syntax:<br>
`for (iterator; condition; iteration) {`<br>
  `logic;`<br>
`}`<br>
In the upcoming steps, you'll explore each component of a loop in detail. For now, construct a `for` loop that includes the terms `"iterator"`, `"condition"`, and `"iteration"` for the three components. Keep the loop body, the section within the curly braces `{}`, empty.

```js
for ("iterator"; "condition"; "iteration"){}
```

## **Step 29** 
Your loop now needs a proper iterator. The iterator is a variable you can declare specifically in your `for` loop to control how the loop iterates or goes through your logic.<br>
It is a common convention to use `i` as your iterator variable in a loop. A `for` loop allows you to declare this in the parentheses `()`. For example, here is a for `loop` that declares an `index` variable and assigns it the value `100`.<br>
`for (let index = 100; "second"; "third") {`<br>
`}`<br>
Replace the string `"iterator"` with a `let` declaration for the variable `i`. Assign it the value `0 `to start. This will give the `i` variable the value `0` the <b>first time<b> your loop runs.

```js
for (let i = 0; "condition"; "iteration") {}
```

## **Step 30** 
The <i>condition</i> of a `for` loop tells the loop how many times it should iterate. When the `condition` becomes false, the loop will stop.<br>
In JavaScript, a Boolean value can be either `true` or `false`. These are not strings - you will learn more about the difference later on.<br>
For now, you will use the <i>less than</i> operator (`<`). This allows you to check if the value on the left is less than the value on the right. For example, `count < 3` would evaluate to `true` if `count` is `2`, and `false` if `count` is `4`.<br>
Replace your "condition" string with a condition to check if i is less than count.

```js
for (let i = 0; i < count; "iteration") {}
```

## **Step 31** 
Your <i>iteration</i> statement will tell your loop what to do with the iterator after each run.<br>
When you reassign a variable, you can use the variable to reference the previous value before the reassignment. This allows you to do things like add three to an existing number. For example, `bees = bees + 3;` would increase the value of `bees` by three.<br>
Use that syntax to replace your `"iteration"` string with a reassignment statement that increases `i` by one.

```js
for (let i = 0; i < count; i = i + 1) {}
```

## **Step 32** 
Your loop should now run eight times. Inside the body of the loop, print the value of the `i` iterator and see what happens.

```js
for (let i = 0; i < count; i = i + 1) {
  console.log(i);
}
```

## **Step 33** 
You should see the numbers zero through seven printed in your console, one per line. This will serve as the foundation for generating your pyramid.<br>
Replace your log statement with a statement to push `i` to your `rows` array.

```js
rows.push(i);
```

## **Step 34** 
Unfortunately, now you cannot see what your loop is doing.<br>
Use `let` to declare a `result` variable, and assign it an empty string. An empty string is represented by quotation marks with nothing between them, such as `""`.

```js
let result = "";
```

## **Step 35** 
Add a log statement to print the value of `result`. Depending on which console you use, you may not see anything printed.

```js
console.log(result);
```

## **Step 36** 
To manipulate the `result` string, you will use a different type of loop. Specifically, a `for...of` loop, which iterates over each item in an iterable object and temporarily assigns it to a variable.<br>
The syntax for a `for...of` loop looks like:<br>
`for (const value of iterable) {`<br>
`}`<br>
Note that you can use `const` because the variable only exists for a single iteration, not during the entire loop.<br>
Create a `for...of` loop to iterate through your `rows` array, assigning each value to a `row` variable.

```js
for (const row of rows){}
```

## **Step 37** 
Remember in your previous loop that you used the addition operator `+` to increase the value of `i` by `1`.<br>
You can do a similar thing with a string value, by appending a new string to an existing string. For example, `hello = hello + " World";` would add the string `" World"` to the existing string stored in the hello variable. This is called concatenation.<br>
In your `for...of` loop, use the addition operator to concatenate the `row` value to the `result` value.

```js
result = result + row; 
```

## **Step 38** 
Now all of your numbers are appearing on the same line. This will not work for creating a pyramid.<br>
You will need to add a new line to each row. However, pressing the return key to insert a line break between quotes in JavaScript will result in a parsing error. Instead, you need to use the special <i>escape sequence</i> `\n`, which is interpreted as a new line when the string is logged. For example:<br>
`lineOne = lineOne + "\n" + lineTwo;`<br
Use a second addition operator to concatenate a new line between the existing `result` value and the added `row` value.

```js
result = result + "\n" + row;
```

## **Step 39** 
Printing numbers won't result in a visually appealing pyramid. Now that you're outputting the formatted content of your `rows` array, it's time to update your original loop.<br>
Instead of pushing `i` to the array, push the value of your `character` variable.

```js
rows.push(character);
```

## **Step 40** 
Now you have a series of `#` characters, but the pyramid shape is still missing. Fortunately, the `i `variable represents the current "row" number in your loop, enabling you to use it for crafting a pyramid-like structure.<br>
To achieve this, you will use the `.repeat()` method available to strings. This method accepts a number as an argument, specifying the number of times to repeat the target string. For example, using `.repeat()` to generate the string `"Code! Code! Code!"`:<br>
`const activity = "Code! ";`<br>
`activity.repeat(3);`<br>
Use the `.repeat()` method on your `character`, and give it `i` for the number.

```js
character.repeat(i);
```

## **Step 41** 
You're getting closer! At this point, you're encountering what's known as an <i>off-by-one</i> error, a frequent problem in zero-based indexing languages like JavaScript.<br>
The first index of your `rows` array is `0`, which is why you start your `for` loop with `i = 0.` But repeating a string zero times results in nothing to print.<br>
To fix this, add `1` to the value of `i` in your `.repeat()` call. Do not assign it back to `i` like you did in your loop conditions.

```js
rows.push(character.repeat(i + 1))
```

## **Step 42** 
The logic for formatting this pyramid is likely going to get complicated, which means it's a great time to extract that code into a function.<br>
A <i>function</i> is a block of code that can be reused throughout your application. Functions are declared with the following syntax:<br>
`function name(parameter) {`<br>
`}`<br>
The `function` keyword tells JavaScript that the name variable is going to be a function. `parameter` is a variable that represents a value that is passed into the function when it is used. A function may have as many, or as few, <i>parameters</i> as you'd like. Like a `for` loop, the space between the curly braces is the <i>function</i> body.<br>
Declare a `padRow` function. Do not create any parameter variables yet. The function body should be empty. Remember that you need to use camel case for your naming convention.

```js
function padRow() {}
```

## **Step 43** 
In order to use a function, you need to call it. A <i>function</i> call tells your application to run the code from the function wherever you choose to call it. The syntax for a function call is the function name followed by parentheses. For example, this code defines and calls a `test` function.<br>
`function test() {`<br>
`}`<br>
`test();`<br>
Call your `padRow` function.

```js
function padRow() {}
padRow();
```

## **Step 44** 
You are calling your `padRow` function, but not doing anything with that function call. All functions in JavaScript <i>return</i> a value, meaning they provide the defined result of calling them for you to use elsewhere.<br>
To see the result of calling your `padRow` function, declare a `call` variable and assign your existing `padRow` call to that variable.

```js
const call = padRow();
```

## **Step 45** 
Now add a log statement to print the value of your `call` variable.

```js
console.log(call);
```

## **Step 46** 
Your `call` variable has an `undefined` value, even though you defined it! This is because your `padRow` function does not currently return a value. By default, functions return `undefined` as their value.<br>
In order to return something else, you need to use the `return` keyword. Here is an example of a function that returns the string `"Functions are cool!"`:<br>
`function demo() {`<br>
  `return "Functions are cool!";`<br>
`}`<br>
Use the `return` keyword to have your function return the string `"Hello!"`.

```js
return "Hello!";
```

## **Step 47** 
When you have a value that is explicitly written in your code, like the `"Hello!"` string in your function, it is considered to be <i>hard-coded</i>. Hard-coding a value inside a function might not make it as reusable as you'd like.<br>
Instead, you can define <i>parameters</i> for the function. Parameters are special variables that are given a value when you call the function, and can be used in your function to dynamically change the result of the function's code.<br>
To add a parameter to your function, you need to add a variable name inside the parentheses. For example, this `demo` function has a `name` parameter:<br>
`function demo(name) {`<br>
`}`<br>
`name` sounds like a useful parameter, so go ahead and add it to your `padRow` function.

```js
function padRow(name)
```

## **Step 48** 
A function does not have to return a hard-coded value. It can return the value stored in a variable. Parameters are special variables for a function, so they can also be returned.<br>
Change your `padRow` function to `return` the `name` parameter directly.

```js
return name;
```

## **Step 49** 
If you open your console again, you'll see that your `padRow` function is returning `undefined`, even though you defined a return value! This is because parameters need to be given a value when you <b>call</b> the function.<br>
When you pass a value to a function call, that value is referred to as an <i>argument</i>. Here is an example of calling a `demo` function and passing `"Naomi"` as the argument for the `name` parameter.<br>
`function demo(name) {`<br>
  `return name;`<br>
`}`<br>
`demo("Naomi");`<br>
Pass your own name as the argument for the `name` parameter in your `padRow` call. Remember that your name is a string, so you'll need to use quotes.

```js
const call = padRow("Joe");
```

## **Step 50** 
Variables in JavaScript are available in a specific <i>scope</i>. In other words, where a variable is declared determines where in your code it can be used.<br>
The first scope is the global scope. Variables that are declared outside of any "block" like a function or f`or` loop are in the <i>global scope</i>. Your character, count, and rows variables are all in the global scope.<br>
When a variable is in the global scope, a function can access it in its definition. Here is an example of a function using a global `title` variable:<br>
`const title = "Professor ";`<br>
`function demo(name) {`<br>
  `return title + name;`<br>
`}`<br>
`demo("Naomi")`<br>
This example would return `"Professor Naomi"`. Update your `padRow` function to return the value of concatenating your `character` variable to the beginning of the `name` parameter.

```js
return character + name;
```

## **Step 51** 
Variables can also be declared inside a function. These variables are considered to be in the <i>local scope</i>, or <i>block scope</i>. A variable declared inside a function can only be used inside that function. If you try to access it outside of the function, you will either get `undefined` or an error.<br>
To see this in action, use `const` to declare a `test` variable in your `padRow` function. Initialise it with the value `"Testing"`.<br>
Then, below your function, try to log `test` to the console. You will see an error because it is not defined outside of the function's local scope. Remove that `console.log` to pass the tests and continue.

```js
function padRow(name) {
  return character + name;
  const test = "Testing";
}
consoe.log(test)
```

## **Step 52** 
There is a bit of a problem, here. Your `test` declaration is currently after your `return` statement. An important thing to know about the `return` keyword is that it does not just define a value to be returned from your function, it also stops the execution of your function code. This means that any code after a `return` statement will not run.<br>
Move your `test` initialization to the line above your `return` statement.

```js
```

## **Step 53** 
If you try to add a `console.log(test)` call below your `padRow` function, you would see an error. This is because `test` is defined in the local scope, meaning you cannot access it in the global scope (outside of the `padRow` function).<br>
Returning a value from a function brings that value into the scope where the function was called. To bring your `"Testing"` value from the `padRow` function into the global scope, update your return statement to `return` only the `test` variable.

```js
return test;
```

## **Step 54** 
Now your `call` variable has the value `"Testing"`. But your function is no longer using the `name` parameter.<br>
Remove the `name` parameter from your function declaration, then remove your `"CamperChan"` string from the `padRow` call.

```js
const call = padRow("Test");
```

## **Step 55** 
Because your function was no longer using the parameter, changing the value passed in the call did not affect it.<br>
Go ahead and remove the `test` declaration from your `padRow` function. Also, remove the `return` statement, so your function is empty again.

```js
function addTwoNumbers(a, b) {
  return a + b;
}

let sum = addTwoNumbers(5, 10);
console.log(sum);
```

## **Step 56** 
As expected, your function now returns `undefined` again. Your `call` variable is not necessary any more, so remove the `call` declaration and the `console.log` for the `call` variable.

```js
```

## **Step 57** 
In order to know how to format a row, your `padRow` function will need to know which row number you are on, and how many rows in total are being generated.<br>
The best way to do this is by creating function parameters for them. Give your `padRow` function a `rowNumber` and `rowCount` parameter. Multiple parameters are separated by a comma:<br>
`function name(first, second) {`<br>
`}`

```js
function padRow(rowNumber, rowCount)
```

## **Step 58** 
Remember in an earlier step, you learned about return values. A function can <i>return</i> a value for your application to consume separately.<br>
In a function, the `return` keyword is used to specify a return value. For example, this function would return the value given to the first parameter:<br>
`function name(parameter) {`<br>
  `return parameter;`<br>
`}`<br>
Use the `return` keyword to return the value of the `character` variable, repeated `rowNumber` times.

```js
return character.repeat(rowNumber);
```

## **Step 59** 
A <i>function call</i> allows you to actually use a function. You may not have been aware of it, but the methods like `.push()` that you have been using have been function calls.<br>
A function is called by referencing the function's name, and adding `()`. Here's how to call a `test` function:<br>
`test();`<br>
Replace the `character.repeat(i + 1)` in your `.push()` call with a function call for your `padRow` function.

```js
rows.push(padRow());
```

## **Step 60** 
Your `padRow` function has two parameters which you defined. Values are provided to those parameters when a function is called.<br>
The values you provide to a function call are referred to as <i>arguments</i>, and you <i>pass</i> arguments to a function call. Here's a function call with `"Hello"` passed as an argument:<br>
`test("Hello");`
Pass `i + 1` and `count` as the arguments to your `padRow` call. Like parameters, arguments are separated by a comma.

```js
rows.push(padRow(i + 1, count))
```

## **Step 61** 
You should now see the same bunch of characters in your console. Your `padRow` function is doing the exact same thing you were doing earlier, but now it's in a reusable section of its own.<br>
Use the addition operator to concatenate a blank space `" "` to the beginning and end of your repeated `character` string.

```js
```

## **Step 62** 
Now it is time for a bit of math. Consider a three-row pyramid. If we want it centered, it would look something like:<br>
`··#··`<br>
`·###·`<br>
`#####`<br>
Empty spaces have been replaced with interpuncts, or middle dots, for readability. If you extrapolate the pattern, you can see that the spaces at the beginning and end of a row follow a pattern.<br>
Update your blank space strings to be repeated `rowCount - rowNumber` times.<br>
Open up the console to see the result.

```js
return " ".repeat(rowCount - rowNumber) + character.repeat(rowNumber) + " ".repeat(rowCount - rowNumber);
```

## **Step 63** 
You can pass full expressions as an argument. The function will receive the result of evaluating that expression. For example, these two function calls would yield the same result:<br>
`test(2 * 3 + 1);`<br>
`test(7);`<br>
Looking at the pattern again:<br>
`··#··`<br>
`·###·`<br>
`#####`<br>
Update the `character` value to be repeated `2 * rowNumber - 1 times.`<br
Open up the console again to see the updated result.

```js
return " ".repeat(rowCount - rowNumber) + character.repeat(2 * rowNumber - 1) + " ".repeat(rowCount - rowNumber);
```

## **Step 64* 
Your pyramid generator now functions as expected. But this is an excellent opportunity to further explore the code you have written.<br>
The addition operator is not the only way to add values to a variable. The <i>addition assignment</i> operator can be used as shorthand to mean "take the original value of the variable, add this value, and assign the result back to the variable." For example, these two statements would yield the same result:<br>
`test = test + 1;`<br>
`test += 1;`<br>
Update your iterator statement in the `for` loop to use addition assignment.

```js
for (let i = 0; i < count; i += 1)
```

## **Step 65** 
Because you are only increasing `i` by `1`, you can use the <i>increment operator</i> `++`. This operator increases the value of a variable by 1, updating the assignment for that variable. For example, `test` would become `8` here:<br>
`let test = 7;`<br>
`test++;`<br>
Replace your addition assignment with the increment operator for your loop iteration.

```js
for (let i = 0; i < count; i++) 
```

## **Step 66** 
Rather than having to pass `i + 1` to your `padRow` call, you could instead start your loop at `1`. This would allow you to create a one-indexed loop.<br>
Update your iterator to start at `1` instead of `0`.

```js
for (let i = 1; i < count; i++)
```

## **Step 67** 
The pyramid looks a little funny now. Because you are starting the loop at `1 instead of 0`, you do not need to add one to `i` when you pass it to `padRow`.<br>
Update the first argument of your `padRow` call to be `i`.

```js
rows.push(padRow(i, count));
```

## **Step 68** 
Unfortunately, now the bottom of the pyramid has disappeared. This is because you have created another <i>off-by-one error</i>.<br>
Your original loop went for `i` values from `0` to `7`, because `count` is `8` and your condition requires `i` to be less than `count`. Your loop is now running for `i` values from `1` to `7`.<br>
Your loop needs to be updated to run when `i` is `8`, too. Looking at your logic, this means your loop should run when `i` is <i>less than or equal to</i> `count`. You can use the less than or equal to operator `<=` for this.<be>
Update your loop condition to run while `i` is less than or equal to `count`.

```js
for (let i = 1; i <= count; i++)
```

## **Step 69** 
Comments can be helpful for explaining why your code takes a certain approach, or leaving to-do notes for your future self.<br>
In JavaScript, you can use `//` to leave a single-line comment in your code.<br>
Add a single-line comment above your function to remind yourself to change the code to a different kind of loop.

```js
//change code to a different kind of loop
```

## **Step 70** 
JavaScript also has support for multi-line comments. A multi-line comment starts with `/*` and ends with `*/`.<br>
Unlike a single-line comment, a multi-line comment will encapsulate multiple lines.<br>
Use `/*` and `*/` to turn your current `for` loop, including the body, into a multi-line comment.

```js
/*for (let i = 1; i <= count; i++) {
  rows.push(padRow(i, count));
}*/
```

## **Step 71** 
Your pyramid has disappeared again. That's okay - that is to be expected.<br>
Before you create your new loop, you need to learn about `if` statements. An <i>`if` statement</i> allows you to run a block of code only when a condition is met. They use the following syntax:<br>
`if (condition) {`<br>
  `logic`<br>
`}`<br>
Create an `if` statement with the boolean `true` as the condition. In the body, print the string `"Condition is true"`.

```js
if (true) {
  console.log("Condition is true")
}
```

## **Step 72** 
You'll see the string printed in the console, because `true` is in fact true.<br>
Change the condition of your `if` statement to the boolean `false`.

```js
if (false)
```

## **Step 73** 
Now the string is no longer printing, because `false` is not `true`. But what about other values?<br>
Try changing the condition to the string `"false"`.

```js
if ("false")
```

## **Step 74** 
The text has appeared again! This is because `"false"` is a string, which when evaluated to a boolean becomes `true`. This means `"false"` is a truthy value.<br>
A <i>truthy value</i> is a value that is considered true when evaluated as a boolean. Most of the values you encounter in JavaScript will be truthy.<br>
A <i>falsy value</i> is the opposite - a value considered false when evaluated as a boolean. JavaScript has a defined list of falsy values. Some of them include `false`, `0`, `""`, `null`, `undefined`, and `NaN`.<br>
Try changing your `if` condition to an empty string `""`, which is a falsy value.

```js
if ("")
```

## **Step 75** 
The text is gone again! Empty strings evaluate to `false`, making them a <i>falsy value</i>. You will learn more about truthy and falsy values in future projects.<br>
For now, remove your `if` statement entirely. Use `let` to declare a `continueLoop` variable and assign it the boolean `false`. Then use `let` to declare a `done` variable and assign it the value `0`.

```js
let continueLoop = false;
let done = 0;
```

## **Step 76** 
A <i>`while`</i> loop will run over and over again until the `condition` specified is no longer true. It has the following syntax:<br>
`while (condition) {`<br>
  `logic;`<br>
`}`<br>
Use that syntax to declare a `while` loop with `continueLoop` as the condition. The body should be empty.

```js
while (continueLoop){}
```

## **Step 77** 
Right now, if you change `continueLoop` to true, your `while` loop will run forever. This is called an <i>infinite loop</i>, and you should be careful to avoid these. An infinite loop can lock up your system, requiring a full restart to escape.<br>
To avoid this, start by using the increment operator to increase the value of the `done` variable inside your loop.

```js
while (continueLoop) {
  done++;
}
```

## **Step 78** 
The <i>equality</i> operator `==` is used to check if two values are equal. To compare two values, you'd use a statement like `value == 8`.<br>
Add an `if` statement to your loop. The statement should check if `done` is equal to `count` using the equality operator.

```js
if (done == count){}
```

## **Step 79** 
The equality operator can lead to some strange behavior in JavaScript. For example, `"0" == 0` is true, even though one is a string and one is a number.<br>
The <i>strict equality</i> operator `===` is used to check if two values are equal and share the same type. As a general rule, this is the equality operator you should always use. With the strict equality operator, `"0" === 0` becomes false, because while they might have the same value of zero, they are not of the same type.<br>
Update your `done == count` condition to use the strict equality operator.

```js
if (done === count)
```

## **Step 80** 
When `done` has reached the value of `count`, we want the loop to stop executing.<br>
Inside your `if` body, assign the boolean `false` to your `continueLoop` variable.

```js
continueLoop = false;
```

## **Step 81** 
To make your pyramid generate again, push the result of calling `padRow` with `done` and `count` as the arguments to your rows array, similar to what you did in your first loop.

```js
rows.push(padRow(done, count));
```

## **Step 82** 
The <i>strict inequality</i> operator `!=`= allows you to check if two values are not equal, or do not have the same type. The syntax is similar to the equality operator: `value !== 4`.<br>
Update your `while` loop condition to check if `done` is not equal to `count`.

```js
while (count !== done)
```

## **Step 83** 
Since you have moved the comparison into the `while` condition, you can remove your entire `if` statement.

```js
```

## **Step 84** 
Your loop is no longer relying on the `continueLoop` variable. This makes the variable an <i>unused declaration</i>. Generally, you want to avoid unused declarations to prevent future confusion.<br>
Remove your `continueLoop` variable.

```js
```

## **Step 85** 
Your pyramid generator is still working. However, it could be possible to end up with an infinite loop again.<br>
Because you are only checking if `done` is not equal to `count`, if `done` were to be <b>larger</b> than count your loop would go on forever.<br>
Update your loop's condition to check if `done` is less than or equal to `count`.

```js
while (done <= count)
```

## **Step 86** 
Using `done` to track the number of rows that have been generated is functional, but you can actually clean up the logic a bit further.<br>
Arrays have a special `length` property that allows you to see how many values, or <i>elements</i>, are in the array. You would access this property using syntax like `myArray.length`.<br>
Update your condition to check if `rows.length` is less than or equal to `count`.

```js
while (rows.length <= count)
```

## **Step 87** 
You can also replace the `done` reference in your `padRow` call.<br>
Note that `rows.length` here would give you an off-by-one error, because `done` is incremented <i>before</i> the call.<br>
So you'll need to replace `done` here with `rows.length + 1`. When you do this, you may see a `Range Error`, because we've created another off-by-one error.<br>
You'll need to change the `while` condition to use the less than operator, instead of the less than or equal operator.

```js
while (rows.length < count) {
  done++;
  rows.push(padRow(rows.length + 1, count));
}
```

## **Step 88** 
Now you no longer need your `done` variable. Remove the increment operation from your loop, and the variable declaration for `done`.

```js
```

## **Step 89** 
That's a very clean and functional loop. Nice work! But there's still more to explore.<br>
Use a multi-line comment to comment out your while loop.

```js
/*while (rows.length < count) {
  rows.push(padRow(rows.length + 1, count));
}*/
```

## **Step 90** 
What if you made your pyramid upside-down, or <i>inverted</i>? Time to try it out!<br>
Start by creating a new `for` loop. Declare your iterator `i` and assign it the value of `count`, then use the boolean `false` for your condition and iteration statements.

```js
for (let i = count; false; false) {}
```

## **Step 91** 
Because you are going to loop in the opposite direction, your loop needs to run while `i` is greater than `0`. You can use the greater than operator > for this.<br>
Set your loop's condition to run when `i` is greater than `0`.

```js
for (let i = count; i > 0; false)
```

## **Step 92** 
Your iteration statement is also going to be different. Instead of adding `1` to `i` with each loop, you need to subtract `1`.<br>
Like you did earlier with `i = i + 1`, update your iteration statement to give `i` the value of subtracting `1` from itself.

```js
for (let i = count; i > 0; i = i - 1)
```

## **Step 93** 
Again, push the result of calling `padRow` with your `i` and `count` variables to your `rows` array.<br>
Open up the console to see the upside-down pyramid.

```js
rows.push(padRow(i, count));
```

## **Step 94** 
Just like addition, there are different operators you can use for subtraction. The <i>subtraction assignment</i> operator `-=` subtracts the given value from the current variable value, then assigns the result back to the variable.<br>
Replace your iterator statement with the correct statement using the subtraction assignment operator.

```js
for (let i = count; i > 0; i -= 1)
```

## **Step 95** 
Because you are only subtracting one from `i`, you can use the <i>decremen operator</i> `--`.<br>
Replace your subtraction assignment with the decrement operator.

```js
for (let i = count; i > 0; i--)
```

## **Step 96** 
Use a multi-line comment to comment out this loop as well, to prepare for the next approach.

```js
/*for (let i = count; i > 0; i--) {
  rows.push(padRow(i, count));
}*/
```

## **Step 97** 
You can actually build the inverted pyramid without needing to loop "backwards" like you did.<br>
To do this, you'll need to learn a couple of new array methods. Start by using `const` to declare a `numbers` variable. Assign it an array with the elements `1`, `2`, and `3`. Then log the `numbers` array.

```js
const numbers = [1,2,3]
console.log(numbers)
```

## **Step 98** 
The `.unshift()` method of an array allows you to add a value to the <b>beginning</b> of the array, unlike `.push()` which adds the value at the end of the array. Here is an example:<br>
`const numbers = [1, 2, 3];`<br>
`numbers.unshift(5);`<br>
The `numbers` array would now be `[5, 1, 2, 3]`.<br>
Use `const` to declare an `unshifted` variable, and assign it the result of calling `.unshift()` on your `numbers` array. Pass `5` as the argument. Then print your `unshifted` variable.

```js
const unshifted = numbers.unshift(5);
console.log(unshifted);
```

## **Step 99** 
Notice that like `.push()`, `.unshift()` returns the new length of the array after the element is added.<br>
Arrays also have a `.shift()` method. This will remove the <b>first</b> element of the array, unlike `.pop()` which removes the last element. Here is an example of the `.shift()` method:<br>
`const numbers = [1, 2, 3];`<br>
`numbers.shift();`<br>
The `numbers` array would be `[2, 3]`.<br>
Declare a `shifted` variable, assign it the result of calling `.shift()` on your `numbers` array, and print the variable.

```js
const shifted = numbers.shift(5);
console.log(shifted)
```

## **Step 100** 
Now that you've tried these methods, you can do another inverted pyramid approach. But first you need to clean up your experimentation.<br>
Remove your `numbers` array, and the method calls and log calls.

```js
```

## **Step 101** 
Sometimes you may wish to bring back previous code that you commented out. You can do so by removing the `/*` and `*/` around that code. This is called <i>uncommenting</i>.<br>
Uncomment only your first `for` loop. Leave the single line comment and the other two multi line comments in place.

```js
```

## **Step 102** 
Your pyramid is no longer inverted. This is because you are adding new rows to the <b>end</b> of the array.<br>
Update your loop body to add new rows to the beginning of the array.

```js
rows.unshift(padRow(i, count));
```

## **Step 103** 
What if you had a way to toggle between an inverted pyramid and a standard pyramid?<br>
Start by declaring an `inverted` variable, and assigning it the value `true`. You are not changing this variable in your code, but you will need to use `let` so our tests can modify it later.

```js
let inverted = true;
```

## **Step 104** 
Use an `if` statement to check if `inverted` is true. Remember that you do not need to use an equality operator here.

```js
if (inverted){}
```

## **Step 105** 
Now move your `.unshift()` call into your `if` block.

```js
```

## **Step 106** 
Sometimes you will want to run different code when an `if` condition is false. You can do this by adding an `else` block. An `else` block will only evaluate if the `if` block does not evaluate.<br>
The syntax to add an `else` block is:<br>
`if (condition) {`<br>
  `logic`<br>
`} else {`<br>
  `logic`<br>
`}`<br>
Add an `else` block to your `if` block.

```js
else{}
```

## **Step 107** 
When `inverted` is false, you want to build a standard pyramid. Use `.push()` like you have in previous steps to achieve this.

```js
rows.push(padRow(i, count));
```

## **Step 108** 
Your pyramid generator is now in a finished state, with more functionality than you originally planned! The next step is to clean up your code.<br>
Remove all comments, both single- and multi-line, from your code.

```js
```

## **Step 109** 
Nice work! Experiment with different values for your `character`, `count`, and `inverted` variables.<br>
When you are ready to move on to your next project, set `character` to `"!"`, `count` to `10`, and `inverted` to `false` to continue.<br>
Congratulations on completing your first JavaScript project!

```js
const character = "!";
const count = 10;
let inverted = false;
```
