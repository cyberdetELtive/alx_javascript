HTML and JavaScript Form Validation Project
This repository contains a collection of HTML and JavaScript projects focused on form validation. Each project addresses a specific form validation task. Below are instructions and information about each task along with their respective files and directories within the repository.

Task 0: Password Strength Validation
File: 0-password-strength.js, password.html

Description:
In this task, we aim to validate the strength of a password entered in a form. The JavaScript file 0-password-strength.js contains the validation logic, while the HTML file password.html provides the form structure.

Instructions:

Implement JavaScript validation for password strength when the form is submitted.
Create a function called validatePassword to check the password against the following criteria:
At least 8 characters long.
Contains at least one uppercase letter.
Contains at least one lowercase letter.
Contains at least one numeric digit.
Contains at least one special character (e.g., !@#$%^&*).
Display an error message in the <p> element with the id "error" if the password does not meet the criteria.
Allow form submission if the password meets all the criteria.

Task 1: Email Format Validation
File: 1-email-validation.js, email.html

Description:
This task focuses on validating the format of an email address entered in a form. The JavaScript file 1-email-validation.js contains the validation logic, while the HTML file email.html provides the form structure.

Instructions:

Implement JavaScript validation for email format when the form is submitted.
Create a function called validateEmail to check if the email follows the standard email format.
Display the error message "Please enter a valid email address" in the <p> element with the id "error" if the email format is incorrect.
Prevent the default form submission behavior using JavaScript if the email format is not valid.

Task 2: Dynamic Form Field Generation
File: 2-dynamic-form.js, dynamic-form.html

Description:
In this task, you'll create a form with a dynamic number of text input fields based on the selected value in a dropdown menu. The JavaScript file 2-dynamic-form.js contains the logic for generating and validating the form, while the HTML file dynamic-form.html provides the form structure.

Instructions:

Implement JavaScript to generate a dynamic number of text input fields based on the selected value in the dropdown menu.
Create a function called generateInputFields to generate the specified number of text input fields dynamically within the "inputContainer" div.
Implement JavaScript validation to ensure that all dynamically generated fields are filled before submitting the form.
Create a function called validateForm to validate the form before submission. Display the error message "Please fill in all fields" if any field is empty.

Task 3: Form Submission Handling and Validation
File: 3-form-submission.js, form-submission.html

Description:
This task involves handling form submissions and performing validation before submission. The JavaScript file 3-form-submission.js contains the logic for form submission handling and validation, while the HTML file form-submission.html provides the form structure.

Instructions:

Implement JavaScript to handle form submission and perform validation.
Create a function called handleFormSubmit to handle the form submission.
Add an event listener to the form element to listen for the "submit" event and call the handleFormSubmit function.
Prevent the default form submission behavior using event.preventDefault().
Retrieve the values entered in the form fields using JavaScript.
Use JavaScript validation to ensure that all required fields (e.g., "name" and "email") are filled.
Display error messages and a success message based on validation results.