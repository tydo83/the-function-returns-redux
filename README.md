# The Function Returns

### Setup

1. Navigate to this directory in your terminal.
2. Run `code .` to open the project in VS Code.
3. Open `main.test.js` (you can use Command-P to start typing in the name!).
3. In a terminal (preferably a full-screen one), run `jest --watch-all` to start testing.


### Workflow

You'll be working in **`main.test.js`**, creating the variables needed with the values asked for, according to the specifications given in the tests. Check your terminal for feedback on which aspect of the problem you have yet to complete, and read the specifications' actual code implementation for extra help; it makes explicit exactly what outputs are expected given the test inputs.


### Guidelines:

* Please do **not** call the functions; just declare them! You can call them to check for your own testing purposes, but then either delete or comment out the line.


### Tasks

##### Global Variables, just to refresh us on the old way of doing things.

* Create a variable named `greeting` and give it the value 'Hello'.
* Create a variable named `sum` and give it the value 0.
* Create a variable named `prod` and give it the value 0.
* Create a function named  `greet` that will take one parameter (of type string). The function will change the value of `greeting` to 'Hello' followed by a space followed by the value of the parameter.
* Create a function named  `sumOfTwo` that will take two parameters (of type number). The function will change the value of `sum` to be equal to the sum of the two parameters
* Create a function named  `multiply` that will take three parameters (of type number). The function will change the value of `prod` to be equal to the product of the three parameters.


##### Let's RETURN stuff.

* Create a function named  `sayHi` that will take one parameter and return a personalized greeting

   INPUT:  sayHi("Charlotte"); 

   OUTPUT:  "Hello Charlotte!";

   INPUT:  sayHi("Colin"); 

   OUTPUT:  "Hello Colin!";

* Create a function named  `returnWhatISay` that will take a string sentence and returns that sentence

   INPUT:  returnWhatISay("Hello students, how are you"); 

   OUTPUT:  "Hello students, how are you";

* Create a function named  `divide` that will take two parameters and return the result

   INPUT:  divide(10,5); 

   OUTPUT:  2;

* Create a function named `remainder` that takes two parameters and return the remainder that we get when those two numbers get divided

   INPUT:  remainder(10,3); 

   OUTPUT:  1;
