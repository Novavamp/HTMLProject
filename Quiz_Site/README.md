# Accessibility Quiz

**Author:** Precious Nwosu

## Description
This project is an HTML/CSS quiz with a focus on accessibility practices. It contains questions related to HTML and CSS, along with student information input fields. The quiz aims to test and improve knowledge of accessibility concepts in web development.

## Code Explanations

### HTML Structure
- The project uses semantic HTML elements for proper document structure and accessibility. Key elements include:
  - `<header>`: Contains the logo, quiz title, and navigation links.
  - `<main>`: Wraps the quiz content.
  - `<form>`: Used to collect student information and quiz responses.
  - `<section>`: Role regions are used to group related content.
  - `<h2>`: Headings provide semantic structure to sections.

### Student Information
- The student information section includes input fields for Name, Email, and Date of Birth (D.O.B.).
- Labels (`<label>`) are associated with their respective input fields using the `for` attribute.
- For D.O.B., a `<span>` with a class of `sr-only` is used to provide screen reader users with additional context.

### HTML Questions
- HTML questions are grouped within fieldsets (`<fieldset>`) with legends for context.
- Each question includes a list of radio button choices.
- The `name` attribute is used to group radio buttons for each question.
- Labels for radio buttons are associated using the `for` attribute.
- Radio buttons have `value` attributes set to "true" or "false" for evaluation.

### CSS Questions
- The CSS questions section includes a dropdown select field and a textarea for additional comments.
- The select field is required and includes options for "Yes" and "No."
- The textarea provides space for users to input comments or questions.

### Accessibility
- The project follows accessibility best practices, including:
  - Properly labeled form fields for screen reader users.
  - Use of ARIA roles and landmarks to improve navigation.
  - Semantic HTML elements for structure and headings.
  - Keyboard navigation and focus styles for interactive elements.
  - Alt text provided for images.

## Usage
1. Clone or download the project repository to your local machine.
2. Open the `index.html` file in a web browser to access the quiz.
3. Fill in the student information fields including Name, Email, and Date of Birth.
4. Answer the HTML and CSS questions provided in the quiz.
5. Select "Yes" or "No" for the frontend developer question.
6. Optionally, provide additional comments or questions in the textarea field.
7. Click the "Send" button to submit your responses.

## Contact
For any inquiries or feedback, please contact Precious Nwosu at [preciousgabraels2@gmail.com](mailto:preciousgabraels2@gmail.com).