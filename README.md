
Built by https://www.blackbox.ai

---

```markdown
# Shipping History Tracker

## Project Overview
The Shipping History Tracker is a web-based application designed for businesses to manage and view their shipping history. Users can register an account, log in, and search for shipping records based on specific criteria. This application aims to provide an easy way to track shipments and associated details in one centralized platform.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/shipping-history-tracker.git
   cd shipping-history-tracker
   ```

2. **Set up the database:**
   - Edit `config.php` to update the database connection parameters (`$host`, `$user`, `$pass`, `$db`).
   - Run `setup_database.php` in your web browser or command line to create the necessary database tables. Make sure to delete this file after setup for security reasons.

3. **Web Server:**
   - Ensure you have a local server environment (like XAMPP, MAMP, or a live server) that supports PHP and MySQL.

4. **Create an uploads directory:**
   - The application will create an `uploads` directory automatically if it does not exist. Ensure it has the correct permissions (e.g., `0755`).

5. **Access the application:**
   - Navigate to `http://localhost/shipping-history-tracker/index.php` in your web browser to start using the application.

## Usage

- **Registration:** Create a new account by filling out the registration form on `register.php`.
- **Login:** Use your credentials to access the main dashboard on `index.php`.
- **Dashboard:** Once logged in, you can search for shipping records using the search form. The results will display a table with details about the shipments that match the criteria.

## Features

- User registration and authentication.
- Dashboard for viewing shipping history.
- Search functionality for filtering shipping records by Customer PO and comments.
- Responsive design using Tailwind CSS for improved user experience.

## Dependencies

- PHP (version >= 7.4)
- MySQL (MySQLi extension)
- Tailwind CSS (for styling)

## Project Structure

```
shipping-history-tracker/
│
├── config.php               # Database configuration and connection script
├── index.php                # Login page
├── register.php             # User registration page
├── logout.php               # Logout functionality
├── dashboard.php            # Main dashboard for viewing shipping records
├── setup_database.php       # Database setup script (delete after use)
└── uploads/                 # Directory for file uploads (created automatically)
```

### Security Notes
- Ensure you take appropriate security measures to protect user data and credentials.
- Never expose sensitive files like `config.php` and `setup_database.php` in a production environment.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing
Contributions are welcome! Please create a pull request or open an issue for any enhancements or bugs you find.
```