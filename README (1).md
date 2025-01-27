
# Employee Management System

A comprehensive web application designed to manage employee data efficiently, utilizing a React frontend, Node.js backend, and MySQL database.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Secure login system for administrators.
- **Employee Management**: Add, view, update, and delete employee records.
- **Category Management**: Organize employees into categories for better management.
- **Responsive Design**: Accessible on various devices.

## Project Structure

```
Employee-Management-System/
├── ReactFrontEnd/       # React application
└── ServerSide/          # Node.js server and API
```

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/YousafKhan1/Employee-Management-System-in-React-Node-MySQL.git
   cd Employee-Management-System
   ```

2. **Backend Setup**:

   - Navigate to the server directory:

     ```bash
     cd ServerSide
     ```

   - Install dependencies:

     ```bash
     npm install
     ```

   - Configure the MySQL database:

     - Ensure MySQL is installed and running.
     - Create a database named `employee_management`.
     - Update the database configuration in `config/db.js` with your MySQL credentials.

   - Run database migrations (if applicable) to set up tables.

   - Start the server:

     ```bash
     npm start
     ```

     The server will run on `http://localhost:5000`.

3. **Frontend Setup**:

   - Navigate to the React application directory:

     ```bash
     cd ../ReactFrontEnd
     ```

   - Install dependencies:

     ```bash
     npm install
     ```

   - Start the React application:

     ```bash
     npm start
     ```

     The application will run on `http://localhost:3000`.

## Usage

- **Login**: Access the admin panel using your credentials.
- **Dashboard**: View a summary of employees and categories.
- **Manage Employees**: Add new employees, edit existing records, or remove employees as needed.
- **Manage Categories**: Create and organize categories to classify employees.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m 'Add new feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request detailing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Note**: Ensure that all configurations, such as database credentials and API endpoints, are correctly set up before running the application. For detailed tutorials and walkthroughs, you can refer to the following resources:

- Part 1 Video Tutorial: [https://youtu.be/IKQQIYDfyPc](https://youtu.be/IKQQIYDfyPc)
- Part 2 Video Tutorial: [https://youtu.be/6a4B7ev3vd0](https://youtu.be/6a4B7ev3vd0)

For further assistance or support, feel free to reach out or open an issue in the repository.
