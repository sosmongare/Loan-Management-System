# Loan-Management-System
Loan Management System is a Web-based application build using Laravel. The system also automates savings, borrowing, and payment transactions. Most cooperatives, mini-banks, micro-finance banks, and other financial institutions utilize this program to manage loan and savings activities.
# How to install
Clone the repository
Create a new database to store info.
Rename .env.example  to .env
Configure database information in the .env file

# Open command
Run composer: composer update
Generate key by running: php artisan key:generate
Run migration to create and populate table: php artisan migrate --seed
Run the application: php artisan serve
