avaScript Projects - README
This repository contains a series of JavaScript projects focused on various concepts, including lexical scoping, closures, DOM manipulation, and asynchronous execution using setTimeout. Below, you'll find a brief description of each project along with instructions on how to run and test them.

Project 0: Lexical Scoping and Welcome Message
Description:
In this project, you'll create a function called welcome that takes two arguments, firstName and lastName. It will display a welcome message with the full name in an alert box.

How to Test:
Open your web inspector in the tab “Console”.
Copy and paste the code from 0-welcome.js into the console and hit enter.
Execute welcome('Holberton', 'School'); in the console. This should trigger an alert with the message "Welcome Holberton School!".
When you execute alert(fullName) afterwards, it should return a reference error because fullName is not defined in the global scope.
Project 1: Closure Scope Chain
Description:
This project explores closure and scope chaining. It involves nested functions and demonstrates how inner functions have access to variables in outer functions.

How to Test:
Copy and paste the code from 1-nested_functions.js into your web console.
Execute outer() in the console.
Observe the sequence of alert messages that display the text "Welcome", "Welcome Holberton", and "Welcome Holberton!".
Project 2: Closure
Description:
In this project, you'll create a closure function called welcomeMessage that accepts a fullName argument. It generates an alert displaying a welcome message with the provided name. You'll also create three instances of this closure.

How to Test:
Copy and paste the code from 2-function_me.js into your web console.
Execute guillaume(), alex(), and fred() in the console.
You should see three alerts with the welcome messages for Guillaume, Alex, and Fred.
Project 3: Closure and Loops
Description:
This project involves creating a closure that generates a sequence of student seat numbers. It demonstrates how closures can capture and maintain state.

How to Test:
Copy and paste the code from 3-classrooms.js into your web console.
Execute console.log(classRoom[0]()), console.log(classRoom[3]()), and console.log(classRoom[9]()) in the console.
You should see the seat numbers 1, 4, and 10 printed to the console.
Project 4: Complex Closure
Description:
This project explores the concept of closures to create functions that perform addition and division operations. Four closures are created, each with a different behavior.

How to Test:
Copy and paste the code from 4-math.js into your web console.
Execute console.log(addBy100(20)), console.log(divideBy10(20)), console.log(divideBy100(200)), and console.log(addBy1000(20)) in the console.
You should see the expected results printed to the console.
Project 5: Changing DOM with Closure
Description:
This project demonstrates using closures to change the style of a web page. Different modes (Spooky, Dark mode, Scream mode) are implemented by altering CSS properties.

How to Test:
Copy and paste the code from 5-mode.js into an HTML file or your browser's console.
Open the HTML file in your browser or execute the code in the browser console.
Click the "Spooky," "Dark mode," and "Scream mode" buttons to see the corresponding style changes.
Project 6: Private Methods with Closure
Description:
In this project, you'll create a module named studentHogwarts that demonstrates private variables and methods using closures. You'll create two student instances and manipulate their scores.

How to Test:
Copy and paste the code from 6-hogwarts.js into your web console.
Observe the console output, which displays the scores of Harry and Draco.
Project 7: Stack Order and setTimeout
Description:
This project explores the execution order of JavaScript code with setTimeout. It logs messages in a specific sequence to illustrate asynchronous behavior.

How to Test:
Copy and paste the code from 7-timeout.js into your web console.
Observe the console output, which should display the messages in the specified order.
Feel free to explore and experiment with these JavaScript projects to gain a better understanding of lexical scoping, closures, DOM manipulation, and asynchronous execution. Enjoy coding!