# Daily Reading 7

#### Explain why we need domain modeling.

Domain modeling, and usage of objects, allow for you to make small targeted changes to values, and have the output be reflected without any issue, for similar problems, or the same problem with different parameters.

#### Why should tables not be used for page layouts?

Screen readers will be confused by them, and not function correctly, generating an accessibility concern for your site. Assembling a page using tables is more complicated, and uses more tags, making maintenence difficult, and to top it all off, several aspects of context aware autoformmating will fail.

#### List and describe 3 different semantic HTML elements used in an HTML `<table>`.

`<tr>` for Table row. Creates one horizontal row on a table, which will contain a number of `<th>` elements that make up the table's cells.

`<tbody>` for Table Body. `<tr>`s and `<th>`s are nested in this to show that these particular elements create the data of the table, and are not part of the key or labeling system.


#### What is a constructor and what are some advantages to using it?
A constructor is a higher level version of making an object. Instead of hand making an object each time, make a function that can be fed values and a name, that then builds an object with that name. the `new` keyword is used for constructors.

#### How does the term `this` differ when used in an object literal versus when used in a constructor?
I'm having trouble figuring this out. It's hard to google. I think the constructor lets the object literal use the this keyword in order to refer to itself, instead of the constructor? which allows for better usage of constructing object literals that require the `this`?

#### Explain prototypes and inheritance via an analogy from your previous work experience. NOTE: This is a very common front end developer interview question

Is Prototype a sort of nested space that values can be tucked into, that is shared between objects? This is really complicated, and I'm gonna just take the L on this one.

I'll update this later. Probably.



#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)