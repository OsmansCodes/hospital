# Hospital Management System (HMS) Project Wiki

## Overview
The Hospital Management System (HMS) is a web-based application designed to streamline the management of hospital operations. It provides functionalities for patients, doctors, and administrators to manage appointments, medical history, and other hospital-related activities.

## Project Structure

### Root Directory
- `index.php`: The main entry point of the application.
- `PROJECT_WIKI.md`: This documentation file.

### Assets
Contains static resources such as stylesheets, JavaScript files, fonts, and images.
- `css/`: Contains CSS files for styling.
- `js/`: Contains JavaScript files for interactivity.
- `images/`: Contains image assets.
- `scss/`: Contains SCSS files for styling.
- `webfonts/`: Contains font files.

### HMS Directory
Contains the core PHP files for the application.
- `appointment-history.php`: Displays appointment history for users.
- `book-appointment.php`: Allows users to book appointments.
- `change-emaild.php`: Enables users to change their email address.
- `change-password.php`: Allows users to change their password.
- `check_availability.php`: Checks the availability of doctors.
- `dashboard.php`: Displays the user dashboard.
- `edit-profile.php`: Allows users to edit their profile.
- `forgot-password.php`: Handles password recovery.
- `get_doctor.php`: Fetches doctor details.
- `logout.php`: Logs out the user.
- `manage-medhistory.php`: Manages medical history.
- `registration.php`: Handles user registration.
- `reset-password.php`: Resets the user password.
- `user-login.php`: Handles user login.
- `view-medhistory.php`: Displays medical history.

#### Admin Subdirectory
Contains PHP files for administrative functionalities.
- `about-us.php`: Displays information about the hospital.
- `add-doctor.php`: Allows admin to add new doctors.
- `appointment-history.php`: Displays appointment history for admin.
- `between-dates-reports.php`: Generates reports for a specific date range.
- `change-password.php`: Allows admin to change their password.
- `dashboard.php`: Displays the admin dashboard.
- `manage-doctors.php`: Manages doctor profiles.
- `manage-patient.php`: Manages patient profiles.
- `manage-users.php`: Manages user accounts.
- `query-details.php`: Displays user queries.

### Other Directories
- `doctor/`: Contains files specific to doctor functionalities.
- `include/`: Contains reusable PHP components.
- `master/`: Contains master templates.
- `vendor/`: Contains third-party libraries and dependencies.

## Features
- User registration and login.
- Appointment booking and management.
- Medical history tracking.
- Doctor and patient management.
- Admin dashboard for hospital operations.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, SCSS
- **Backend**: PHP
- **Database**: MySQL

## How to Run
1. Install [XAMPP](https://www.apachefriends.org/index.html) or any other PHP server.
2. Place the project folder in the `htdocs` directory.
3. Start the Apache and MySQL services from the XAMPP control panel.
4. Import the database using the provided `.sql` file.
5. Access the application via `http://localhost/hospital` in your web browser.

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear messages.
4. Submit a pull request for review.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any queries or support, please contact [zahidislam375@.com](mailto:zahidislam375@.com]).