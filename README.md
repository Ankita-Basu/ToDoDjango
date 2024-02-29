# To-Do List Django Project

This Django project implements a simple To-Do List application. Users can create, update, and delete tasks, mark them as complete, and filter tasks based on their status. The project follows the Model-View-Controller (MVC) architecture provided by Django.

## Features:
1. **Task Management:** Create, update, and delete tasks effortlessly.
2. **Status Tracking:** Mark tasks as complete or incomplete.
3. **Filtering:** Easily filter tasks based on their completion status.
4. **User Authentication:** Securely manage tasks with user-specific accounts.

## Setup:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/todo-list-django.git

   
2. **Navigate to the project directory:**

    ```bash
    cd todo-list-django
    
3. **Create a virtual environment:**

    ```bash
    python -m venv venv
   
4. **Activate the virtual environment:**

       On Windows:
            
                    ```bash
                    venv\Scripts\activate
           
         On macOS/Linux:
           
            ```bash
            source venv/bin/activate


5. **Install dependencies:**

    ```bash
    pip install -r requirements.txt

6. **Apply database migrations:**

    ```bash
    python manage.py migrate

7. **Run the development server:**

    ```bash
    python manage.py runserver

8. **Access the application in your browser at http://127.0.0.1:8000/.**

##Usage:
Create a superuser to manage the admin panel:

    ```bash
    python manage.py createsuperuser
Visit the admin panel at http://127.0.0.1:8000/admin/ to manage tasks.

Use the To-Do List interface at http://127.0.0.1:8000/todo/ to interact with tasks.

##Contributing:
Contributions are welcome! Feel free to open issues or pull requests for improvements.