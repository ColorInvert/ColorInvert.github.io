## What is Git?

Git is a type of Distributed Version Control System. (DVCS) The purpose of a DVCS is to provide several different safeguards and good practices when working
on a computer application or most any system that requires code, and updates.

Some of the core benifits of DVCS are: 
- preventing a single hard drive failing from taking out the source code of a project,
- allowing multiple people to work on thesame project at the same time with minimal conflicts,
- and maintaining access to all previous versions that can be reverted to at will, as insurance against a bad update being distributed.

### Version Control

The Version Control part of DVCS is somewhat self explantatory, Git will keep track of all previous versions and changes made to a project, as well as
automatically document the exact lines of code in which something has changed from one "build" to the next. With this precise documentation and tracking,
diagnosing the source, origin, and reason for an error in between versions is a lot easier, along with allowing painless revert to old versions if needed.

### Distributed, Push, and Pull.

The distributed part of DVCS refers to the fact that if you are working on a project, and need the most recent up to date version to work on, instead of
asking a central computer for the original files, it makes a copy of the most recent version of the project for you, and allows you to work on that.
This is called a **Pull Request,** since you are pulling data from the main archive. (Often called the Main Branch)
If you make changes that you are satisfied with, and are ready to provide a new version to the central archive, you can send in your work through the
use of a **Push Request,** which is you communicating that "I have a new version, with these changes. During this time, has anyone else touched any
of the data that I was working on, that would lead to conflicts?"

If no conflicts are detected, then your push request will be accepted, the version number will be updated, and any future pull requests will now recieve
the updated version that you have just provided.

Through these systems, an individual working on a project will not slow down work of others working on the same project, and a catastrophic failure of
a computer that has done a pull request will only lose the data worked on since their last Push to the central system.

[Back To Main Page.](https://colorinvert.github.io/reading-notes/)
