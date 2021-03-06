# _{Application Name}_

#### By Anastasiia Riabets and Jack Jones

#### _{Brief description of application}_

## Technologies Used

* _List all_
* _the major technologies_
* _you used in your project_
* _here_

## Description

_{This is a detailed description of your application. Give as much detail as needed to explain what the application does as well as any other information you want users or other developers to have.}_

## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_

_{Leave nothing to chance! You want it to be easy for potential users, employers and collaborators to run your app. Do I need to run a server? How should I set up my databases? Is there other code this application depends on? We recommend deleting the project from your desktop, re-cloning the project from GitHub, and writing down all the steps necessary to get the project working again.}_

## Tests 

Describe: luhnAlgorithm()

Test: "It should return "This card number is valid." if there are 16 numbers in the input"
Code:
luhnAlgorithm("4102 0808 8043 5620");
Expected Output: "This card number is valid."

Test: "It should return number with every other digit being doubled."
Code:
luhnAlgorithm("4102 0808 8043 5620");
Expected Output: "4204 016016 8046 51220"

Test: "It should return number with every other digit being doubled and summed if it is a double-digit number."
Code:
luhnAlgorithm("4102 0808 8043 5620");
Expected Output: "4204 0707 8046 5320"

Test: "It should return sum of all the digits"
Code:
luhnAlgorithm("4102 0808 8043 5620");
Expected Output: "52"

Test: "It should return "This card number is valid." if the number ends in a zero"
Code:
luhnAlgorithm("4102080860435620");
Expected Output: "This card number is valid."

Test: "It should return "This card number is not valid." if the number does not end in a zero"
Code:
luhnAlgorithm("4102080880435620");
Expected Output: "This card number is not valid."

Describe: company()

Test: "It should return "American Express" if the card number begins with 34 or 37"
Code: company("3402080880435620")
Expected Output: "American Express"

Test: "It should return "Visa" if the card number begins with 4"
Code: company("4102080880435620")
Expected Output: "Visa"

Test: "It should return "Mastercards" if the card number begins with 5"
Code: company("5102080880435620")
Expected Output: "Mastercards"

Test: "It should return "Discover Cards" if the card number begins with 6"
Code: company("6102080880435620")
Expected Output: "Discover Cards"

Describe: length()

Test: "It should return "This card number is valid." if the length is 16 and the company is Visa, Mastercard, or Discover"
Code: length("6102080880435620")
Expected Output: "This card number is valid."

Test: "It should return "This card number is valid." if the length is 15 and the company is American Express"
Code: length("340208088043562")
Expected Output: "This card number is valid."
## Known Bugs

* _Any known issues_
* _should go here_

## License

_{Let people know what to do if they run into any issues or have questions, ideas or concerns.  Encourage them to contact you or make a contribution to the code.}_

Copyright (c) 01/18/2022 Anastasiia Riabets and Jack Jones