### Javascript is known for being a Just In Time programming language with widespread use for adding interactivity and logic systems into webpages.

First, lets get the most easily misunderstood part out of the way:
**The `Javascript` programming language, is completely distinct from, and with different use cases and syntax, than the `"Java"` programming language.**
**Please bear in mind that these two are different, and that the following relates exclusively to `Javascript`!**

#### Variable support, and user input handling

Javascript has standard support for Variables, through 3 different declare types, listed below

- `var x = 5;`

- `let y = 6;`

- `const z = 7;`

The `var` version of variable declaration is actually being phased out, so while it is what is used for old systems, and working with 2015 or earlier stuff will have you run into it, it is recommended that you **do not use it for declaring your variables**

The `let` version of variable declaration is the modern equivelent of `var`, and is for declaring and setting the value of a variable. This variable can be changed through subsequent declarations of it's new value, through or arithmatic functions, such as `y = y + 1`, which would take the value of y and, well, add one to it, before saving the result as the new value of y.

The `const` version of variable declaration is largely similar to let and var, except **const declares a variable that cannot be changed,** even with subsequent declarations.
This means that for the following code block, there are two seperate actions that will *not* work and produce an error.

```
const w = 5;

w = w + 4;      //ERROR

const w = 13;   //ERROR
```

Javascript also has support for logic gates and general flowchart logic, as well as support for arrays and a large number of useful user interaction functions on webpages, such as `prompt()` which can be used to ask the user for a typed response to a popup box, that can then be captured as a variable and used in your code.

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)
