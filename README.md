# Online Registration Form using Laravel

This is a simple online registration form built using the Laravel framework. Users can submit their information, and upon submission, their data will be stored in a database, and they will receive a confirmation email.

## Prerequisites

- PHP and Composer installed on your system.
- SMTP email settings for sending confirmation emails.

## Installation

1. Clone this repository or create a new Laravel project.
2. Configure your `.env` file with the database and mail settings.
3. Run migrations to set up the database tables:php artisan migrate

To start the development server run 
php artisan serve

## Usage
Access the registration form at http://localhost:8000/registration.
Fill in the required information: Name, Phone (11 digits), and Email (gmail.com or yahoo.com only).
Click "Register" to submit the form.
Upon successful registration, a confirmation email will be sent to the provided email address.

## Contributors
oluwasola Peter
