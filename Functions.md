### Functions are a commmonly used shortcut in programming, that save a large amount of time and labor, by being small snippets of code that can be used in multiple contexts. They support being provided arguments, allowing them to have utility even if the task needed is not exactly the same.

A function in javascript is established by providing the `function` keyword, the name of your function (which follows all of the name convention rules that variables do) and a pair of `()`.

A quick example would be:

```
function addem (value1, value2) {
    return value1 + value2;
}
```

The function above, is named `addem` and will add the two arguments you provide, and then `return` the result. The values desired by `addem` can be provided by calling the function in the following way:

```
addem(3,15)
```

Calling this function will make the computer jump over to the location where the function was declared and described, perform the code contained within until it reaches a `return`, and then pass the value created to the location where the function took place.

lets look at one last example, that shows a potential use case:

```
playersScore = addem(10,35) - 25;
```

In the above, the value of an existing variable `playersScore` is updated with a new value. This value is `20` because the addem function is run the moment the computer encounters it, and as shown above, it adds together the two arguments it recieves in the parenthesis, which results in 45. this value of 45 is then subtracted by 25, resulting in 20.

The ability to add numbers together, is of course, a feature in practically every programming language that exists, but this example still shows how a function works, and the ways it can be very useful for both code organization, and for automating tedious tasks.

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)
