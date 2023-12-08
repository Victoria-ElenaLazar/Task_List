# Laravel Task List

A simple Task List application crafted with the powerful Laravel framework. Effortlessly create, update, and delete tasks with a user-friendly interface.

Moreover, enhance productivity by marking tasks as completed and effortlessly track creation and update dates.
## Table of Contents

- [Getting Started](#getting-started)

- [Prerequisites](#prerequisites)

- [Installation](#installation)

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Docker](https://www.docker.com/)
- [Composer for dependency management](https://getcomposer.org/)
- PHP 8.0 and later

### Installation

1. Clone the repository:

   ````
   git clone https://github.com/Victoria-ElenaLazar/Task_List
   ````

2. Navigate to the project directory:
    ````
    cd l10-task-list
    ````
   
3. Install dependencies:
   ```
   composer install
   ```
   
4. Copy the .env.example file and rename it to .env. Configure your database connection as needed.


5. Generate application key:
   ```
   php artisan key:generate
   ```
   
6. Start the Docker containers:
   ```
   docker-compose up -d
   ```
   
7. Run the migrations:

   ```
   php artisan make:migration
   ```
   
8. Access the application:
   ```
   php artisan serve
   ```
   Follow the link and take a tour. 
   
