# developer-portfolio-generator

Developer Portfolio Generator is a command line application that takes in a users GitHub user name and favorite color to generate a PDF resume.

This application requires the following NPM modules: 

* fs
* html-pdf / letter formating 
* axios 
* inquirer

Be sure to install using npm i ... followed by the requirements above. Refer to NPM for more specific information on each module.

Initiate by entering node index.js, this will start prompts. Once the user has entered their information via the command line an HTML document is created and then coverted to a PDF. This application is using Axios to get user information from Github's API.

This information includes: 

* User Name 
* Profile Photo
* GitHub Bio 
* Location of Github user
* Link directly to their Github profile
* Link to their personal website or blog 
* The amount of followers/following
* Number of starred repositories 
* Number of Public repositories 

Each time the same users name is entered, the HTML and PDF update. When a new username is entered new files are created for that user. 

Here is a screen shot of what the PDF looks like once coverted: 

![](example.jpg) 