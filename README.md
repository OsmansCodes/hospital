# Hospital Management System

## Project Overview
This project is a web-based Hospital Management System designed to streamline the management of hospital operations. It includes features for managing appointments, patient records, doctor schedules, and administrative tasks.

## Features
- User authentication and role-based access control (Admin, Doctor, Patient).
- Appointment booking and history management.
- Patient medical history tracking.
- Doctor specialization and schedule management.
- Admin dashboard for managing users, doctors, and reports.

## Project Structure
The project is organized as follows:

- **index.php**: Entry point of the application.
- **assets/**: Contains CSS, JavaScript, fonts, and images used in the project.
- **hms/**: Core application files for user and admin functionalities.
  - **admin/**: Admin-specific functionalities like managing doctors, patients, and reports.
  - **doctor/**: Doctor-specific functionalities like viewing appointments and patient history.
  - **include/**: Common include files for database connection and utilities.
  - **master/**: Master templates and layouts.
  - **vendor/**: Third-party libraries and dependencies.

## Installation
1. Clone the repository to your local machine.
2. Set up a local server environment (e.g., XAMPP, WAMP).
3. Import the database file into your MySQL server.
4. Update the database connection settings in the configuration files.
5. Open the project in your browser using the local server URL.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP
- **Database**: MySQL

## How to Contribute
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.