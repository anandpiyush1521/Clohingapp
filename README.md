# Clothing App

This is a Clothing E-commerce application built with React, Redux, Firebase, and Styled Components. The app allows users to browse and purchase clothing items, sign in with Google authentication, and manage their shopping cart.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/clothing-app.git
   cd clothing-app
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add your Firebase configuration:
   ```env
   REACT_APP_FIREBASE_API_KEY=your-api-key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
   REACT_APP_FIREBASE_DATABASE_URL=your-database-url
   REACT_APP_FIREBASE_PROJECT_ID=your-project-id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
   REACT_APP_FIREBASE_APP_ID=your-app-id
   ```

## Usage

1. Start the development server:

   ```sh
   npm start
   ```

2. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Features

- User authentication with Google
- Browse and search for clothing items
- Add items to the shopping cart
- Checkout process
- Responsive design

## Project Structure

.env  
.gitignore  
package.json  
public/  
src/  
 ├── assets/ - Static assets (images, fonts, etc.)  
 ├── components/ - Reusable UI components (e.g., buttons, cards, inputs)  
 ├── pages/ - Pages representing different views of the app  
 ├── redux/ - Redux store, actions, reducers, and state management  
 ├── firebase/ - Firebase configuration and utility functions  
 ├── App.js - Main App component  
 ├── App.css - Global styles  
 ├── index.js - Entry point for React app  
 └── serviceWorker.js - Service worker for PWA support

### Key Files and Directories

- `src/index.js`: Entry point of the application.
- `src/App.js`: Main application component.
- `src/firebase/firebase.utils.js`: Firebase utility functions.
- `src/redux/`: Redux store configuration and actions.
- `src/components/`: Reusable UI components.
- `src/pages/`: Application pages.

## Available Scripts

In the project directory, you can run:

- `npm start`: Runs the app in the development mode.
- `npm test`: Launches the test runner in the interactive watch mode.
- `npm run build`: Builds the app for production to the `build` folder.
- `npm run eject`: Removes the single build dependency from your project.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
