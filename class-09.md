# Daily Reading 9


#### Why are forms so important in web development?
Forms are the primary way that a website can collect information from a user. "Forms" refers to checkboxes, multiple choice dots, written responses, and many others, but requires good understanding of CSS, Javascript, and HTML to be able to use effectively.

#### When designing a form, what are some key things to keep in mind when it comes to user experience?
you **CAN NOT** nest forms inside of each other. Using a single label per form item is preferred as it is more sensible to screen readers, and multiple elements may cause confusion to screen readers, potentially causing their users to mis-submit forms.

#### List 5 form elements and explain their importance.

`<form>` itself is the formal way to begin setting up a web form, and many screenreaders and assistive technology look for these and use specialized hooks for ease of use.

`<fieldset>` is for grouping together several widgets that relate to a single purpose, such as multiple response options to a question.

`<label>` the text label, for your form item, that states it's purpose. the label itself can be clicked alongside the form item.

`<ul>` Unordered lists are used for forms as well, and can be useful for grouping together, alongside fieldset.

`<li>` As are lists. Better for when the ordering of the specific choices also matters, such as some elements having a higher priority than others.
#### How would you describe events to a non-technical friend?

Press the big red button, and the electrical signal that goes to the moon-destroyer beam is sent out, saying to fire. That electrical signal, caused by your action, is an event.

#### When using the addEventListener() method, what 2 arguments will you need to provide?
Type, and Listener. Type is the variety of event we are waiting to occur, and listener is the Thing that should take action upon reciving the "go" signal.

#### Describe the event object. Why is the target within the event object useful?
It allows you to have an element modify itself upon the event listener signal firing, for example a button that changes color upon press, or changes a boolean value to true, and disappears.

#### What is the difference between event bubbling and event capturing?
Event bubbling refers to the "inside out" ordering of event fires when several nested elements all recieve a signal from deep within the nesting.  a button within a div within a body, with all three of them having listeners attached, will activate in the order button-div-body. This is the default behavior.
However, it's possible to make the highest element go first, by having a listener at the highest level fire while the action is in the "capture" phase of the interaction, which comes first and from outside to in.



#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)