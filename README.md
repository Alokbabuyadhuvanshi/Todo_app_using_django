**ToDo Application using Django**

This is a simple ToDo application built using Django, allowing users to create,complete,and delete tasks.

### Getting Started

1. Clone this repository to your local machine:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd todo_django
   ```

3. Create a virtual environment:

   ```
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```
     source venv/bin/activate
     ```

5. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

6. Run migrations to apply database changes:

   ```
   python manage.py migrate
   ```

7. Start the development server:

   ```
   python manage.py runserver
   ```

8. Open your web browser and go to [http://localhost:8000/](http://localhost:8000/) to view the application.

### Features

- **Create Task**: Users can add new tasks with a title and description.
- **Delete Task**: Users can remove tasks from the list.
- **Mark as Completed**: Users can mark tasks as completed.

### Technologies Used

- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **db.SQLite3**: A lightweight relational database management system included as part of Python's standard library.
- **HTML/CSS**: Used for front-end design and structure.
- **Bootstrap**: A popular CSS framework for building responsive and mobile-first websites.

### Directory Structure

- **todoapp/**: Django application directory containing settings, URLs, and other application-specific files.
- **todo/**: Main project directory.
- **templates/**: HTML templates for rendering dynamic content.

### Author

- [Alok Babu yadhuvanshi](https://github.com/alokbabuyadhuvanshi)

### Contributions

Contributions are welcome! Please feel free to submit pull requests or open issues for any bugs or feature requests.

### Acknowledgments

- Inspired by Django's official tutorial.
