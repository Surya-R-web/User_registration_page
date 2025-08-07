 User Registration Page (HTML, CSS, JavaScript)
Goal: Build a responsive user registration form and implement client-side validation with data persistence using localStorage.
Requirements:
Fields: Full Name, Email, Password, Confirm Password
Validations:
Name: Must not contain numbers or special characters (only alphabets and spaces).
Email: Validate against a standard email format using regex.
Password:
Minimum 8 characters
Must include at least one number and one special character
Add a toggle eye icon to show/hide password
Confirm Password: Must match the password field
Behavior:
Enable the Submit button only if all fields are valid
On submission, store the form data in localStorage as an array of user objects
