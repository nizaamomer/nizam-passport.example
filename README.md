# Example Laravel Project

This is an example Laravel project to demonstrate the setup and usage of the Nizam Passport API package. The project showcases how to integrate and use Laravel Passport for API authentication.

## Features

-   **User Authentication:** Register, login, and manage users.
-   **API Authentication:** Secured endpoints using Laravel Passport.
-   **Password Reset:** Functionality to reset passwords via email.
-   **Email Verification:** Users must verify their email addresses before accessing protected routes.
-   **User Profile Management:** Update and manage user profiles.

## Requirements

-   **PHP:** ^7.3|^8.0
-   **Composer:** Latest version
-   **Laravel:** ^8.0|^9.0|^10.0|^11.0
-   **MySQL:** ^5.7|^8.0 or PostgreSQL equivalent

## Installation

Follow these steps to set up the project:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/nizaamomer/nizam-passport.example.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd nizam-passport.example
    ```

3. **Install dependencies:**

    ```bash
    composer install
    npm install
    ```

4. **Set up the environment file:**

    ```bash
    cp .env.example .env
    ```

5. **Generate an application key:**

    ```bash
    php artisan key:generate
    ```

6. **Set up the database:**

    - Create a database in MySQL or PostgreSQL.
    - Update the `.env` file with your database credentials.

7. **Run migrations:**

    ```bash
    php artisan migrate
    ```

8. **Start the development server:**

    ```bash
    php artisan serve
    ```

## Usage

This project provides a simple API for managing users. Here are some of the available API endpoints:

-   **POST /api/auth/register:** Register a new user
-   **POST /api/auth/login:** Log in a user
-   **POST /api/auth/logout:** Log out a user (requires authentication)
-   **POST /api/auth/forgot-password:** Send a password reset link
-   **POST /api/auth/reset-password:** Reset the user's password

-   **GET /api/auth/user:** Get authenticated user information (requires authentication)

## Example Commit

If you want to see the difference in the integration of the Nizam Passport API package, you can view the repository’s commit history [here](https://github.com/nizaamomer/nizam-passport.example/commits/main/).

## Credits

-   **Nizam Omer** - Author and maintainer of the Nizam Passport API package

## Acknowledgements

Thank you for using this example project! Special thanks to My God, everyone who has contributed, tested, and provided feedback. Your support is greatly appreciated. May this project serve as a helpful guide in your Laravel API development journey. 🙏
