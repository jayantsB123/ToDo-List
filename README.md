# ToDo List App

This is a ToDo list application built using React for the frontend, Node.js for the backend, and Firebase for the database. The app allows users to create, update, and delete tasks in a simple and intuitive interface.

## Features

- **User Authentication**: Users can sign up and log in to manage their tasks.
- **Task Management**: Create, update, and delete tasks with ease.
- **Real-time Updates**: Tasks are synchronized in real-time across all devices.

## Technologies Used

- **Frontend**: React.js, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: Firebase Realtime Database
- **Authentication**: Firebase Authentication

## Prerequisites

- Node.js installed
- Firebase project set up with Realtime Database and Authentication enabled

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd todo-list-app
   ```

3. Install dependencies for both frontend and backend:

   ```
   cd client
   npm install
   cd ../server
   npm install
   ```

4. Configure Firebase: Add your Firebase configuration in `server/config/firebaseConfig.js`.

5. Start the development server:

   ```
   cd server
   npm start
   ```

   The app will be accessible at `http://localhost:5000`.

## Usage

1. Register or log in to the application.
2. Add tasks using the provided interface.
3. Update or delete tasks as needed.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README according to the specifics of your project. Make sure to include relevant details about how to set up Firebase configurations, how to handle environment variables, and any other project-specific information.
