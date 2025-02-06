# Chatify

A real-time chat application built with React Native, Socket.IO, and Express. This app allows users to create chat rooms and send messages in real-time.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (Login screen)
- Create and join chat rooms
- Real-time messaging using Socket.IO
- Responsive design for mobile devices
- Clean and intuitive user interface

## Technologies Used

- **Frontend**: 
  - React Native
  - React Navigation
  - Expo
- **Backend**: 
  - Node.js
  - Express
  - Socket.IO
- **Database**: 
  - In-memory storage (for chat rooms)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MonalikaPatnaik/my-chat-app.git
   cd my-chat-app
   ```

2. Install dependencies for the frontend:

   ```bash
   cd my-app
   npm install
   ```

3. Install dependencies for the backend:

   ```bash
   cd server
   npm install
   ```

4. Start the backend server:

   ```bash
   npm run start
   ```

5. Start the frontend application:

   ```bash
   cd my-app
   npx expo start
   ```

## Usage

1. Open the app on your mobile device or emulator.
2. Navigate to the Login screen and enter your credentials.
3. Create a new chat room or join an existing one.
4. Start chatting in real-time with other users.

## Folder Structure

my-app/ # Frontend React Native application
│ ├── components/ # Reusable components
│ ├── screens/ # Application screens
│ ├── utils/ # Utility functions and styles
│ └── App.js # Main application entry point
server/  # Backend Node.js application
│ ├── index.js # Server entry point
│ └── package.json # Backend dependencies

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.
