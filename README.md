# Chatify

A real-time chat application built with React Native, Socket.IO, and Express. This app allows users to create chat rooms and send messages in real-time.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)

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

1. [Fork](https://github.com/MonalikaPatnaik/Chatify/fork) the repository.
   
2. Clone the forked repository:

   ```bash
   git clone https://github.com/<your_github_username>/chatify.git
   cd my-app
   ```

3. Install dependencies for the frontend:

   ```bash
   cd my-app
   yarn install
   ```

4. Install dependencies for the backend:

   ```bash
   cd server
   npm install
   ```

5. Start the backend server:

   ```bash
   npm run start
   ```

6. Start the frontend application:

   ```bash
   cd my-app
   npx expo start
   ```
 7. After running the above command, the development server will start and you can access the application on web on [localhost:8081](http://localhost:8081).   

## Usage

1. Open the app on your mobile device or web application.
2. Navigate to the Login screen and enter your credentials.
3. Create a new chat room or join an existing one.
4. Start chatting in real-time with other users.

## Folder Structure

**my-app/**  _(Frontend React Native application)_ <br/>
**│ ├── components/**  _(Reusable components)_ <br/>
**│ ├── screens/**  _(Application screens)_ <br/>
**│ ├── utils/**  _(Utility functions and styles)_ <br/>
**│ └── App.js**  _(Main application entry point)_ <br/>
**server/**   _(Backend Node.js application)_ <br/>
**│ ├── index.js**  _(Server entry point)_ <br/>
**│ └── package.json**  _(Backend dependencies)_ <br/>

## Contributing

Contributions are welcome. It's the best way to support and get involved in the community! Please follow these steps to contribute:

1. Follow the [installation](#installation) steps.
   
2. Create a new branch
    ```bash
   git checkout -b <your_branch_name>
    ```
3. Make your changes and add them
   ```bash
   git add .
   ```
4. commit your changes
   ```bash
   git commit -m 'Write a meaningful but small commit message'
   ```
5. Push the changes to the branch
   ```bash
   git push -u origin <your_branch_name>
   ```
6. Click on **"Compare And Pull Requests"** and open a pull request.
