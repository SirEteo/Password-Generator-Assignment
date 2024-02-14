# Password-Generator-Assignment

Assignment Criteria
-Generate a password when the button is clicked
-Present a series of prompts for password criteria
-Length of password
    At least 8 characters but no more than 128.
-Character types
    Lowercase
    Uppercase
    Numeric
    Special characters ($@%&*, etc)
-Code should validate for each input and at least one character type should be selected
-Once prompts are answered then the password should be generated and displayed in
an alert or written to the page

How to do...

-The index.html & style.css were provided. A partial done script.js was also provided. The first step was to establish some variables. Variables characterLength=8 and choiceArr was created.

-Create an if statement under the getPasswordOptions()- Using isNaN to make sure the user writes a numeric number and not a word/string. Also making sure the length of the password is within the desired paramaters. If not alert the user to try agaun.

-Create a prompt to ask the user how many character they want. This prompt should only allow for numeric values. 

- Then create a confirm prompt under another if statement asking questions in regards to the desired inclusion of lowercase, uppercase, numeric, and special characters.

-Under the generatePassword() function write a for loop to generate the desired password. Using Math.floor and Math.random to generate the password.

-Under writePassword function create a new variable which equals getPasswordOptions. create an if statement that will return the written password.

Link to the site: https://sireteo.github.io/Password-Generator-Assignment/
