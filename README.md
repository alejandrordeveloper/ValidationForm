# Validation Form

A responsive web form for user registration with real-time validation for username, email, country, phone number, and password fields.

## Features

- **Username**: Must contain at least 1 lowercase letter and 1 number, 6-16 characters.
- **Email**: Must be a valid email format (e.g., user@example.com).
- **Country**: Select from a dropdown list; phone code updates automatically.
- **Phone Number**: Only numbers allowed, 7-10 digits.
- **Password**: Must contain at least 1 uppercase letter, 1 lowercase letter, and 1 number, 6-16 characters.
- **Confirm Password**: Must match the password.
- **Real-time validation**: Fields are validated as you type.
- **Responsive design**: Looks good on desktop and mobile.

## Usage

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Fill out the form. The submit button is enabled only when all fields are valid.
4. On successful submission, a confirmation alert is shown and the form data is logged to the console.

## File Structure

- [`index.html`](index.html): Main HTML file containing the form.
- [`style.css`](style.css): Styles for the form and layout.
- [`script.js`](script.js): JavaScript for form validation and interactivity.
- [`README.md`](README.md): Project documentation.

## Author
Made by [Alejandro Ramírez](https://github.com/alejandrordeveloper)