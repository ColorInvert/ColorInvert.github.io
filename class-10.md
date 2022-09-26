# Daily Reading 10



#### Name some key differences between a Syntax Error and a Logic Error.
A syntax error is when the computer does not understand at all what you were trying to do, and usually comes up at time of compile. Specifically, it is when you mistype, or misspell, or misformat some line of your code that results in your code never starting in the first place. A logic error is when your program runs, but does not do the expected behavior due to an oversight in the overall logic and "flow" of the code.

#### List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
Multiplying a couple of numbers that both contained decimals resulted in floating point inaccuracy to manifest, giving me numbers like 7.200000000003 which was messing up formatting for a chart for the Pat's Salmon Cookies assignment. I believe I solved this by using Math.round() on all of the numbers generated for my table.

#### How will this topic continue to influence your long term goals?
Functional code is rather important. Getting a keen sense of what error codes mean, what causes them, and what conditions can lead to them will allow you to not only diagnose and fix them faster, but help you prevent them from occuring at all, and helping others debug THEIR code.


#### How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
Debugger is a set of tools that lets you keep an eye on changing values, make your code artificially pause right before the known location where the bug occurs, and generally assists in examining the actions your code is taking in a precise and controlled manner.

#### Define what a breakpoint is.
A breakpoint is a manually placed "red light" for you code that will make your program freeze, and wait for the programmer to manually move forward one logic step at a time. This allows you to better see the exact moment your program breaks, and will help you figure out why.

#### What is the call stack?
The call stack lets you know how you got to the line that you are currently on. Which helps make sure that you're getting to your destination correctly, and that your code's flow is as you expect.



#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)