# Daily Reading 1

 
#### Compose a short poem describing how HTTP sends data between computers.

>A client want to read from a 'site<br>
>Through the transmission of data with light<br>
>He asks for a clone<br>
>Of the site he don't own<br>
>And HTTP sends em' those bytes.

(HTTP is a handshake between systems where a client asks for a copy of a website, the website checks the client's authorization to view, and then if approved, sends them the HTML, CSS, and Javascript components of the site to their system, for their viewing.)

#### Describe how HTML, CSS, and JS files are “parsed” in the browser.

HTML is parsed first, and searches for any `<script>` or `<link>` tags contained within that reference CSS and Javascript additions to the webpage. Any that are identified are requested as well, and after retrieving, all located data, loads into memory the HTML, the CSS, and the Javascript, before applying and executing all discovered HTML/CSS/Javascript.

#### How can you find images to add to a Website?

A simple google search can be used for locating suitable images to add to a site, but be sure to choose the option for Creative Commons license to not get anything you do not have the rights to use! Other options also exist, such as the Wikimedia Commons.

#### How do you create a String vs a Number in JavaScript?

A string can be declared as a varible through the method below:

`const MyString = "this is a simple string message!";`

Note the quotation marks around `this is a simple string message!` the quotation marks denote the phrase's status as a string.

Javascript handles numbers using the `float64` format. Numbers can be defined into variables the same way strings are, but WITHOUT the quotation marks:

`const ButtonsClicked = 5;`



#### What is a Variable and why are they important in JavaScript?

A variable is essentially a named container for a value that can be stored, referenced later, and depending on the type, can also be changed. A variable is extremely useful for a large variety of use cases, with a simple example being asking the user their name, and saving their response to provide a personalized greeting message. Variables can also be numbers, allowing you to do things such as track how many times a button has been clicked.


#### What is an HTML attribute?

An attribute refers to a piece of information relating to an element that will not be displayed to the user, but is used by the site. a "href=...." within an element tag is an attribute.

#### Describe the Anatomy of an HTMl element.

`<p>What's up?</p>`
The `<p>` and `</p>` are **opening** and **closing tags**. the text between them is the **Content,** and the entire thing is called an **element.**

#### What is the Difference between `<article>` and `<section>` element tags?

Article is generally used for containing a set of information that stands together as a topic, seperate from the rest of the document, that **can be understood on its own.** A section is generally used for containing an individual aspect of the page that is **supplementary** to the main content, that would not be easily understood without the context provided by the rest of the webpage.

#### What Elements does a “typical” website include?

- A Header to serve as a "title" to your page,
- A nav bar that helps direct users to other pages within your website
- The main content of the site, usually with various article/section/div elements contained within
- A side bar, with additional navigation options provided
- A footer, at the bottom of the page


#### How does metadata influence Search Engine Optimization?

Having accurate and relevant keywords within your metadata for your site will help your discoverability through search engines, in regards to people looking for topics related to the information within your metadata.

#### How is the `<meta>` HTML tag used when specifying metadata?

It is the official method for adding metadata to your webpage, that helps visiting browsers with functionality for defining the character set the website uses, alongside information useful for search engine optimization, such as author, article title, description, and topic, some of which are displayed in a search engine's paragraph below your webpage's article name!



#### What is the first step to designing a Website?

Figuring out, precisely, **what you wish to accomplish with your website.** Do not proceed with design and layout steps until you have a solid grasp on what your website is suppose to be *for*.

#### What is the most important question to answer when designing a Website?

The question above, "what do you wish to accomplish with your website" is everpresent. But also sorting out which aspects of your website should take priority will be a re-occuring balance to achieve. If your goal is to inform people about a topic you are passionate about, you will want to weigh what the very first thing a visitor sees on your webpage, to get their attention, and keep them interested. "What should I prioritise?" will be a constant question.


#### Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

A visitor's User Agent Stylesheet will auto apply custom style information to an `<h1>` element, which may be something they have custom overrides for as a matter of accessability. Not using an `<h1>` element will not allow any visitors' user agent stylesheet to know where your top level heading is located.

#### What are the benefits of using semantic tags in our HTML?

Correct and appropriate use of semantic tags will allow smooth function of client-side accessibility functions like screen readers, is easier to understand then a lot of repeated `<div>` elements, and is considered by crawlers for the sake of search engine optimization.



#### Describe 2 things that require JavaScript in the Browser?

Dynamic interactions between the user and the website, such as updating with an entered name

WebGL, which is used for complex embedded graphics on your page, including 3D support.

#### How can you add JavaScript to an HTML document?

in the main HTML document, a `<script>` element can be used to contain javascript code directly, or hook to a .js file included alongside your HTML and CSS.

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)
