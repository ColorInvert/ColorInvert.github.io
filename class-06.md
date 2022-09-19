# Daily Reading 6


#### How would you describe an object to a non-technical friend you grew up with?

A javascript object is a bundle of traits. Descriptors that are true about a thing. A car object, or Cobject if you will, has the traits like 4wd, a red paintjob, silver rims, 74% gas tank fullness. That kinda thing, you know?

#### What are some advantages to creating object literals?

Very helpful for data transfer. Can send one object instead of several array items, arrays, and such.


#### How do objects differ from arrays?

Objects can be interacted with dot notation, which is a lot easier to keep track of when there's a massive number of potential data points within the object. getting Alice's name by saying person.name as opposed to person[3] or whatever numbered index name happens to be at is much simpler to remember, and takes advantage of autofill of many text editors.

#### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

When an object property name is defined during the runtime itself, referencing it will result in an error. Bracket notation does not have this limitation however.


#### Evaluate the code below. What does the term this refer to and what is the advantage to using this?



```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

"this" in this case is a reference to its own object. Self. This is advantagous because it allows the inner content of the code to be copy pasted, even if the name of the object itself changes between iterations.

#### What is the DOM?
Document Object Model, and it is an interface for using javascript to modify the aspects of a webpage by treating the whole webpage itself as an object, so object-modifying code is able to manipulate and change it on the fly.


#### Briefly describe the relationship between the DOM and JavaScript.
The DOM is distinct from javascript, and is instead a web API that can be used BY javascript (or others!) to make changes to the webpage. The DOM provide a structure that the Javascript can manipulate.


#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)