# Daily Reading 13




#### Why would a developer use local storage for a web application?

HTTP is fundamentally "stateless" which means that if you revisit a website after doing something, any changes you made will be lost. Local storage is one method of saving data, *without* hosting it upon your webpage's server, by saving the information in a small text file that is saved to the *visitor's* computer. This is better known as a Cookie.

#### What information should not be stored in local storage?

A large amount of information in general, as the size limit is 4kb per website.

Vital data for the function of your site, because users that understand web security may very well have cookie saving disabled entirely.

personally identifiable information of either the server owner, or visitor, as cookies store their information in plain text, on the user's computer, in a simple directory.

#### Local storage can store what type of data? How would you convert it to that type before storing?

Local data will save strings only. But this is not to say that strings are the only datatype that can be ultimately saved and reclaimed with some clever workarounds. If you need to save a number value, existing javascript functions can let you turn it into a string, and existing javascript functions can turn strings that you know are number values back into a number. Simply running a conversion to string on your data before passing it into local storage allows you to work around this limitation, as long as you remember to convert it back on the way out!

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)