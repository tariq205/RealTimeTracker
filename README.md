# Full Stack Node.js App

This project is a full-stack application built with Node.js, Express, and EJS for the frontend. It follows the MVC (Model-View-Controller) architecture pattern.

## Project Structure

```
full-stack-nodejs-app
├── src
│   ├── controllers        # Contains the controllers for handling requests
│   ├── models             # Contains the data models and schemas
│   ├── routes             # Contains the route definitions
│   ├── views              # Contains the EJS templates for rendering views
│   └── app.js             # Entry point of the application
├── public
│   ├── css                # Contains CSS styles
│   ├── js                 # Contains client-side JavaScript
│   └── images             # Contains image files
├── package.json           # npm configuration file
├── .env                  # Environment variables
└── README.md              # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd full-stack-nodejs-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Create a `.env` file in the root directory and add your environment variables.
2. Start the application:
   ```
   npm start
   ```
3. Open your browser and go to `http://localhost:3000` to view the application.

## Features

- MVC architecture for better organization of code
- EJS templating for dynamic HTML rendering
- Static file serving for CSS, JavaScript, and images

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.