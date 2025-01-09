# BookIt

**BookIt** is a hotel booking platform designed to simplify the process of reserving accommodations. The platform features three renowned hotels: **Four Seasons**, **AquaViva**, and **Rixos**, offering detailed information about rooms, amenities, and services.

## Features

- Responsive user interface built with **HTML** and **CSS**.
- Backend developed using **PHP** for dynamic interaction.
- **SQL database** integration for managing bookings, user data, and hotel details.
- Secure login and user authentication.
- Real-time room availability and booking management.
- Payment system integration for seamless transactions.
- Reviews and ratings for hotels.

## Technologies Used

- **HTML**: Structure of the web pages.
- **CSS**: Styling for a modern and responsive design.
- **PHP**: Backend scripting to handle server-side logic.
- **SQL**: Database for storing and managing data.
- **XAMPP**: Local server environment for development and testing.

## Installation Instructions

1. Clone this repository:
   ```bash
   git clone git clone [https://github.com/HadeelAbdulrahman/BookIt.git]
   ```

2. Set up XAMPP:
   - Install [XAMPP](https://www.apachefriends.org/index.html).
   - Place the project folder in the `htdocs` directory.

3. Import the database:
   - Open **phpMyAdmin**.
   - Create a new database (e.g., `bookit_db`).
   - Import the `bookit.sql` file from the project folder.

4. Configure the database connection:
   - Open the `config.php` file in the project.
   - Update the database credentials:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "bookit_db";
     ```

5. Start the server:
   - Launch XAMPP and start **Apache** and **MySQL**.
   - Access the website at `http://localhost/BookIt`.

## Contribution Guidelines

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Add feature: feature-name"
   ```
4. Push your branch to GitHub:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request to merge your feature into the `main` branch.

## License

This project is licensed under the [MIT License](LICENSE).
