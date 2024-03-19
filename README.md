# University Management System

## Overview
This is a web application developed using Django to manage students in the School of Computer Science at a university. The application allows users to view a list of students, a list of courses, and detailed information about each course.

## Features
- View list of students
- View list of courses
- Detailed view of each course
- Student enrollment in courses
- Course coordinator management

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/university-management.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run migrations:
    ```bash
    python manage.py migrate
    ```

4. Create a superuser (admin) account:
    ```bash
    python manage.py createsuperuser
    ```

5. Start the development server:
    ```bash
    python manage.py runserver
    ```

6. Access the application at [http://localhost:8000](http://localhost:8000)

## Usage
- Login to the admin panel using the superuser account created in step 4.
- Manage courses, students, and other data through the admin panel.
- Navigate to the respective URLs to view lists and detailed information.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
