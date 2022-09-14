# Daily Reading 3

#### When should you use an unordered list in your HTML document?

An unordered list has, well, no ordering. It is a bulletpointed list where the items contained within are not in any particular order, and do not need to be for their purpose. A shopping list would be a good example, or a list of company values.

#### How do you change the bullet style of unordered list items?

the CSS property list-style-type. There is also "type" but this is deprecated, and should not be used. list-style-type is capable of using emojis even.

#### When should you use an ordered list vs an unorder list in your HTML document?

Ordered lists are to be used when the order of the list matters. If problems arise if an action for a list is taken at random, then an ordered list should be used instead of unordered. Step by step instructions would nessessitate an ordered list.

#### Describe two ways you can change the numbers on list items provided by an ordered list?

You can use nesting, where an ordered list within an ordered list will start from one again. you can also provide the argument start=x to set the startpoint of the counting up of a list.

#### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

The brave knight of Mar-Jinn patrols the outer borders of the safe haven that the other Characters reside within, acting as a first line of defense and making sure nothing reaches the borders in the first place.

Meanwhile, the caring and kind sage Pa-deen stays within the borders, watching over the text, and ensuring that the Characters Within are properly spaced, with none of them pressed up against the fortress walls that Mar-Jinn dutifully protects.

#### List and describe the four parts of an HTML elements box as referred to by the box model.

From centermost, to outermost:

1. Content Box
Where the content is, your image or text usually. How much space should the item *itself* take?
2. Padding Box
The distance between the Content Box, and the Border Box that make up the interface element. Makes sure that the text/image isn't touching the edges!
3. Border Box
Where the actual edges of this interface element are, and what they're styled like.
4. Margin Box
The extra space around the border that makes sure that there's a healthy amount of room between the borders and any other element.

#### What data types can you store inside of an Array?

Numbers, strings, javascript objects, even other arrays.

#### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```
     const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

The people array is a valid array, and the values can be returned by doing

people[x]

with x being pointer for the array item to access, **starting with zero.**

#### List five shorthand operators for assignment in javascript and describe what they do.

<x++> adds one to the numeric value of x.

<x -= y> subtracts the value of y from x, and applies the new value to x.

<x *= y> Multiplies x by the value of y, and applies the new value to x.

<x /= y> Divides x by the value of y, and applies the new value to x.

<x &&= y> returns the value of x only if **both** x **and** y are Truthy. Otherwise will return 0.

#### Read the code below and evaluate the last expression and explain what the result would be and why.

```

     let a = 10;
     let b = 'dog';
     let c = false;

     // evaluate this
     (a + c) + b;

```

Because they are in parenthesis, the values of a and c are added together first, a number and a boolean.
False "as a number" is 0, whereas true "as a number" is 1, so 10 + 0 is 10. after this, the new number (which is still 10) is added to a string, resulting in the string '10dog'.
This is a concatanation of a string and a number.


#### Describe a real world example of when a conditional statement should be used in a JavaScript program.

An ATM system ensuring that an account has enough money in it, AND the ATM itself has the cash.

IF Account value > requested money
AND ATM current funds < requested money
THEN pay out money AND deduct requested money from account value.

#### Give an example of when a Loop is useful in JavaScript.

Prevents the programmer from having to do mass amounts of repeated tasks through automation, reduces the character count for mass tasks.

An example would be needing to print to the console every 3rd item in a 384 item array.

instead of doing more than 100 console.log(bigarray[2]), console.log(bigarray[5]), sorts of statements, you could have a loop with the changing variable as the array pointer, saving a ton of effort, time, and verbosity.

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)