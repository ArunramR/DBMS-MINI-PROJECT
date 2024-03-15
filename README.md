
# TodoList-in-PHP

Welcome to TodoList-in-PHP! This is a simple todo list application built using PHP and MySQL, with basic CRUD operations for tasks, account management (create, delete), and password management. The frontend is developed with HTML and CSS.

### Technologies Used:
- PHP
- MySQL database
- HTML
- CSS

### How to Run:

1. **Install PHP and MySQL:**
   - Make sure you have PHP and MySQL installed on your system. You can download PHP from [here](https://www.php.net/) and MySQL from [here](https://www.mysql.com/).

2. **Create MySQL Database Tables:**
   - You need to create the necessary database tables in MySQL. You can find the SQL script for creating tables in the `create_database.sql` file.

3. **Configure Database Connection:**
   - Open the `database.php` file located in your TodoList project folder.
   - In the `connectdatabase()` function, specify your MySQL database credentials (hostname, username, password, database name).

4. **Start the PHP Server:**
   - Open the command prompt and navigate to the `TodoList` folder in your project directory.
   - Type the following command to start the PHP built-in web server:
     ```
     php -S localhost:4000
     ```
   - This will start the PHP server on port 4000.

5. **Access the Application:**
   - Open your web browser and go to `http://localhost:4000/login.php`.
   - You should now see the login page of the TodoList application.

### Project Structure:
- `login.php`: Handles user login.
- `logout.php`: Handles user logout.
- `newuser.php`: Allows new users to register.
- `database.php`: Contains database connection settings and functions.
- `todo.php`: Manages CRUD operations for todo tasks.
- `valid.php`: Validates user inputs and performs server-side validation.
- `deleteaccount.php`: Handles the deletion of user accounts.
- `create_database.sql`: SQL script for creating the necessary database tables.
- `changepassword.php`: Allows users to change their account passwords.
- `adduser.php`: Contains functionality for adding new users.
- Other PHP files for task management and user account operations.

### Additional Notes:
- Ensure that your MySQL server is running before accessing the application.
- Make sure you have appropriate permissions set for file read/write operations.
- Consider securing sensitive data such as passwords by using environment variables or a secure configuration file.

### Support:
For any issues or queries, please feel free to raise an issue or contact the project maintainers.

### Contributor:
- [ARUN RAM R](https://github.com/ArunramR)
- [stuckpixel0](https://github.com/stuckpixel0)
- [Victor Ikechukwu Agughasi](https://github.com/Victor-Ikechukwu)

## Happy TodoListing!

---
