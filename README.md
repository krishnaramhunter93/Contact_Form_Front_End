# Contact Form Web Application

## Overview
This is a simple contact form web application designed using HTML, CSS, and JavaScript. It allows users to enter their details and preview their submission before confirming and submitting the form.

## Features
- User-friendly interface with a responsive design.
- Form validation for required fields (name, email, phone number, message).
- Preview feature to review input before submission.
- Radio buttons for preferred contact method selection.
- Dropdown menu to choose the inquiry type.
- Confirmation popup upon successful form submission.
- JavaScript validation to ensure correct input format.

## Technologies Used
- HTML
- CSS
- JavaScript

## Project Structure
```
|-- index.html    # Main HTML file containing the contact form
|-- styles.css    # CSS file for styling (integrated within index.html)
|-- script.js     # JavaScript file for form validation and interactions (integrated within index.html)
|-- README.md     # Documentation for the project
```

## How to Run the Project
1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Fill in the required fields in the form.
4. Click submit to preview the input.
5. Confirm submission to display the success popup.

## Form Validation
- **Name**: Required field, must not be empty.
- **Email**: Must follow the correct email format (e.g., user@example.com).
- **Phone Number**: Must be exactly 10 digits.
- **Message**: Required field, must not be empty.
- **Preferred Contact Method**: Required selection.
- **Inquiry Type**: Must be selected from the dropdown.

## JavaScript Functionality
- `previewForm(event)`: Validates input fields, displays errors if any, and shows the preview box.
- `submitForm()`: Confirms submission and displays the success popup.
- `closePopup()`: Closes the success popup and resets the form.

## Future Enhancements
- Store submitted data in a database.
- Implement backend handling with PHP/Node.js.
- Add CAPTCHA for spam protection.

## Author
**Ram Bajagain**

## License
This project is open-source and free to use.