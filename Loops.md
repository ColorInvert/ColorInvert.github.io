
### Control flow refers to the path that a computer takes when interpreting your code, and is, as a rule of thumb, from top to bottom.

With code, positioning and order matters. the computer when interpreting your code will read top to bottom, left to right, in the same way west germanic languages do.

While methods to exist to make the computer "jump" from one spot in your code to another, ensuring you do so in a way that is sensible and minimizes needless jumps is encouraged as a simple matter of legibility. If your code can generally be read top to bottom without jumping around too much, it's significantly easier for others, or yourself in the future to make sense of the specific actions the computer is taking in what order. This makes debugging much more simple. The order in which the computer interprets your code is known as the **control flow**. Lets discuss the common ways that control flow will deviate from a simple top to bottom path.

### Loops

A loop is a chunk of code that will "capture" the computer's attention into a single code block, and have it read through it repeatedly until told otherwise. They primarily take the form of `for` loops, and `while` loops, which serve different purposes.

a `while` loop requires you to define a variable, and a type of comparison check to perform against it. The loop will repeat until this comparison results in a boolean `false` value. Creating this `false` value is (generally) achieved by making sure the value you define is increased by one each time the end of the loop is reached, which makes your variable essentially a simple counter for how many loops have passed. Be sure to make sure that a boolean `false` result is possible at all, because if you do not, your computer will stay trapped in this loop, which will **crash your browser since the code never ends**.


A `for` loop is similar, but the conditions for escaping the loop are defined in advance, with the value change of your variable dictated at the formation of the loop, in the form of **initialization, expression, increment.** Here is an example, with these three parts explained.
```
for(counter=1; counter < 10; counter++) {
    //do a thing
}
```

**Initialization** is where you define the variable to be compared, which is our `counter=1;`.

**Expression** is the `counter < 10;`, which is checked at the start of each loop. Since counter is (hopefully) increasing in value each loop, eventually this statement will go from true to false, which breaks the loop.

**Increment** is the `counter ++` segment of the code. `counter++` is just a quick shorthand for saying "Add 1 to the value of counter," which makes it a more elegant way to say `counter = counter + 1`.

Once again, **ensure that your counting system for breaking the loop will ever result in a `false`, because if you don't the computer will get stuck in the loop, causing your browser to become entirely unresponsive.**

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)
