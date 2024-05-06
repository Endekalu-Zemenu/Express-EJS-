# Name Letters Counter

This is a simple web application that calculates the number of letters in a user's name. It's built with HTML, EJS templates, and Node.js with the Express framework for the backend.

## Setup Instructions

1. Clone the repository to your local machine:
```
git clone https://github.com/Endekalu-Zemenu/Express-with-EJS
```
2. Navigate to the project directory:
```
cd Express-with-EJS
```
3. Install dependencies:
```
npm install
```
4. Start the server:
```
node index.js
```

5. Open your web browser and go to `http://localhost:3000` to view the application.

## File Map

- **README.md**: This document providing setup instructions and an overview of the project.
- **package.json**: Manages project dependencies and configurations.
- **index.js**: Contains the backend logic implemented with Express framework.
- **views/index.ejs**: EJS template for front-end rendering.

## HTML Documentation

The main EJS template for the front-end is `index.ejs`. It includes:

- Structure for the main page.
- Conditional rendering based on the presence of the `counter` variable.
- A form for users to input their first and last names.

## Backend Documentation

The backend logic is implemented in `index.js` using Express:

- Sets up routes to handle HTTP requests.
- Renders the main page ("/") and handles form submission ("/submit").
- Calculates the total number of letters in the user's inputted names.

## Additional Notes

- Ensure you have Node.js installed on your machine before running the application.
- EJS is used for dynamic content rendering.
- Customize the application as per your requirements.
- Consider deploying the application on a suitable hosting platform for production use.
- Refer to the source code and comments within the files for more details.
