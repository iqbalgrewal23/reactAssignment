# HTTP5222 Assignment 2

This project is a React application developed for the HTTP5222 Assignment 2, which interacts with the API created in Assignment 1.

## Project Structure

```
http5222-assignment-2
├── public
│   ├── index.html        # Main HTML file for the React application
│   └── favicon.ico       # Favicon for the website
├── src
│   ├── components        # Reusable components
│   │   └── ExampleComponent.jsx
│   ├── pages             # Main pages of the application
│   │   └── HomePage.jsx
│   ├── services          # API request functions
│   │   └── api.js
│   ├── App.jsx           # Main application component
│   ├── index.jsx         # Entry point of the application
│   └── styles            # CSS styles
│       └── App.css
├── package.json          # npm configuration file
├── .gitignore            # Files and directories to ignore by Git
├── README.md             # Project documentation
└── vite.config.js        # Vite configuration file
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd http5222-assignment-2
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and go to `http://localhost:3000` to view the application.

## Description

This application is designed to fetch and display data from the API developed in Assignment 1. It includes a main page (`HomePage`) that utilizes reusable components and styles to present the data effectively. The project is structured to facilitate easy maintenance and scalability.