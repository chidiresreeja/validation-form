Form Validation Project
A responsive web application for client-side form validation using HTML, CSS, Bootstrap, and JavaScript.
Table of Contents

Description
Features
Usage
Technologies
Contributing
Acknowledgments

Description
The Form Validation Project is a web application that implements client-side form validation to ensure data integrity and provide a smooth user experience. The application validates user input in various form fields based on predefined criteria and displays real-time error messages to guide users to enter valid data.
Features

Form Field Validation: The application validates the following form fields:
Full Name (minimum 5 characters)
Email (valid email format with '@' character)
Phone Number (10-digit number, cannot be '1234567890')
Password (minimum 8 characters, cannot be 'password' or the user's name)
Confirm Password (must match the entered password)
Real-time Error Messages: Appropriate error messages are displayed when any of the validation criteria are not met, providing clear feedback to the user about the required input format.
CAPTCHA Verification: The form includes a CAPTCHA checkbox to verify that the user is a human and not a bot, enhancing security and preventing automated form submissions.
Responsive Design: The application utilizes Bootstrap for responsive design, ensuring a consistent and user-friendly experience across different devices and screen sizes.
Clear and Readable Code: The codebase is well-organized and follows best practices, with clear separation of concerns between HTML, CSS, and JavaScript files. Comments are included throughout the code to enhance readability and maintainability.

Usage
To use the Form Validation application:
Open the index.html file in a web browser.
Fill out the form fields with the required information.
As you type or when you submit the form, the application will validate the input.
If any validation fails, the corresponding error message will be displayed.
Make sure to check the "I'm not a robot" checkbox before submitting the form.
Once all validations pass, you can submit the form, and a success message will be displayed.

Technologies
The Form Validation project is built using the following technologies:
HTML5
CSS3
Bootstrap 4
JavaScript (ES6)

Contributing
Contributions to the Form Validation project are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. To contribute, follow these steps:
Fork the repository
Create a new branch: git checkout -b feature/your-feature
Make your changes and commit them: git commit -m 'Add your feature'
Push to the branch: git push origin feature/your-feature
Submit a pull request

Acknowledgments
The Form Validation project utilizes the following third-party resources:
Bootstrap for the responsive design framework
Font Awesome for the icon used in the CAPTCHA checkbox
