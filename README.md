# Kanban Board


## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contribution](#contribution)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description

Kanban Board is a web application designed for agile teams to manage tasks and workflows efficiently. This project integrates a secure authentication system using JSON Web Tokens (JWT) to ensure that only authorized users can access the board. Built with a robust backend and an intuitive user interface, it streamlines task management while maintaining security.

## Features

- Secure login page with JWT-based authentication.
- Task management with Kanban-style ticket organization.
- Automatic redirection to the login page for unauthenticated users.
- Session timeout handling with JWT invalidation.
- Persistent user authentication using local storage.
- Polished, user-friendly interface for agile teams.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BrandonLanes/kanban-board

2. Navigate to the project directory:
   cd kanban-board

3. Install dependencies for both the server and client:
   npm install

4. Create a .env file in the server directory and include the following:
   DATABASE_USERNAME=your_database_username
   DATABASE_PASSWORD=your_database_password
   JWT_SECRET=your_secret_key

5. Set up the database:
   - Create a new database
   - Use the provided schema files to initialize tables. 

6. Start the server:
   npm run start:server

7. Start the client:
   npm run start:client

## Usage

1. Open your browser and navigate to the application’s URL.

2. Log in using your credentials to access the Kanban board.

3. Manage tasks by creating, updating, and organizing tickets.

4. Log out to securely end your session.

## Technologies Used
   - Node.js
   - Express.js
   - React
   - JWT (JSON Web Tokens)
   - PostgreSQL
   - Render

## Contribution
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and open a pull request or create an issue.

   1. Fork the project.

   2. Create your feature branch (git checkout -b feature/AmazingFeature).

   3. Commit your changes (git commit -m 'Add some AmazingFeature').

   4. Push to the branch (git push origin feature/AmazingFeature).

   5. Open a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
The wonderful TA's and Dan Mueller for all their assistance.

Bootcamp Tutors 

AI - Xpert Learning Assistant, AskBCS Learning Assistant, ChatGPT