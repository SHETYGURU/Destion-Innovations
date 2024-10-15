# Destion Innovations LLP Dashboard

This is a responsive company dashboard for **Destion Innovations LLP** that provides an overview, latest news, and services sections. The project is built using **React.js** with **Tailwind CSS** for styling and **Firebase** for authentication. It also features a **dark/light mode toggle**, a mobile-responsive layout, and a logout functionality.




## Features

- **Responsive Design**: Optimized for both desktop and mobile screens.
- **Dark/Light Mode Toggle**: Switch between dark and light modes.
- **Dynamic Sections**: Toggle between "Overview," "News," and "Services."
- **Mobile Menu**: A collapsible menu for mobile devices.
- **Firebase Authentication**: Simple authentication with Firebase.
- **Logout Functionality**: Users can sign out, which redirects them to the signup page.
- **Smooth Transitions**: Uses transitions for smooth UI changes like theme toggles.

## Installation

To set up the project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/destion-innovations.git

   ```
   
2. Navigate to the project directory:
   ```bash
   cd destion-innovations
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file at the root of your project and add your Firebase credentials(here the database deatils are displayed ):
  

## Firebase Setup

To use Firebase authentication in this project, follow these steps:

1. Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. Enable **Authentication** and choose **Email/Password** as the sign-in method.
3. Copy your Firebase config values (API Key, Auth Domain, etc.) and add them to your `.env` file as shown in the [Installation](#installation) section.
4. Install the Firebase SDK:
   ```bash
   npm install firebase
   ```

## Usage

To run the project locally, use:

```bash
npm start
```

This will start the development server, and you can view the project in the browser at `http://localhost:3000`.

### Main Functionalities

- **Dark/Light Mode**: You can toggle the theme between dark and light modes using the switch at the top-right corner.
- **Navigation**: Navigate between the "Overview," "News," and "Services" sections using the navbar buttons.
- **Mobile Menu**: The mobile menu is accessible via the hamburger icon and supports the same section navigation.
- **Logout**: Clicking the "Logout" button will sign out the user and redirect them to the signup page.

## Project Structure

```
├── public
│   ├── assets
│   │   └── logo.png         # Company logo
│   └── index.html           # HTML entry point
├── src
│   ├── components
│   │   └── Dashboard.js      # Main  component
│   ├                          # Firebase configuration file
│   ├── App.js                # Main application entry point
│   ├── index.js              # React DOM rendering
│   └── styles                # Global styles or Tailwind configuration
├── .env                      # Environment variables (Firebase credentials)
└── package.json              # Project dependencies and scripts
```

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling the application.
- **Firebase**: Backend service used for authentication and database.
- **React Router**: For handling page navigation.

