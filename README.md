# To-Do Django App

This is a simple **Django** application to manage a to-do list. Users can add, edit, and delete tasks, as well as mark tasks as completed. The app includes a **Django Admin Panel** where you can manage the to-do list directly.

## Key Features:
- Add, edit, delete, and mark tasks as completed.
- View your to-do list at [http://127.0.0.1:8000/todos/](http://127.0.0.1:8000/todos/).
- Use the Django Admin Panel to manage tasks.

---

## Installation

Follow these steps to set up the app locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/justmhie/to-do-django.git
   ``` 

2. **Navigate to the project folder:**
   ```bash
   cd to-do-django
   ```

3. **Set up a virtual environment:**
   ```bash
   python3 -m venv venv
   ```

4. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply the database migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (to access the admin panel):**
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the Django development server:**
   ```bash
   python manage.py runserver
   ```

Your app should now be live at `http://127.0.0.1:8000/`.

---

## Viewing the To-Do List

You can view your to-do list at [http://127.0.0.1:8000/todos/](http://127.0.0.1:8000/todos/). Here, you can see all your tasks and their current statuses.

## Django Admin Panel

You can also manage your to-do list directly from the **Django Admin Panel**. To access the admin panel:

1. Start the development server using the command above.
2. Go to [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/).
3. Log in using the superuser credentials you created in step 6.
4. From there, you can add, edit, and delete tasks.

---

## Deployment on AWS Lightsail

For instructions on how to deploy this app to **AWS Lightsail**, check out my [Dev.to blog](https://dev.to/your_blog_link).
