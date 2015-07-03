## Basic Website Template

File structure created for ease of use when starting new static, front-end project.
Perfect for a github.io portfolio project.

### Getting Started

**Requirements**
* Bower

Navigate to project directory in the terminal. From there:

`cd libs`

`bower install`

This installs the external libraries for the project.
Be sure to link new libraries in the .html if needed.

**SUPER IMPORTANT NOTE ABOUT THIS**

Before finally committing your repo to Github or anywhere else really for production (using git), be sure to delete the
`libs/bower_components`
line from the .gitignore file otherwise none of your libraries will deploy. The reason why this is in the .gitignore is because there is no need to have an entire library inside of your Github repo. It is bad practice and messy, so this is the solution!

Open the index.html file with your browser of choice and start developing.
Have fun!
