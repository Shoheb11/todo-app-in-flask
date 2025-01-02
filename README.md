# Flask To-Do App

This is a simple To-Do application built using Flask. The app allows users to manage their tasks with basic CRUD (Create, Read, Update, Delete) operations.

## Features

- **Add Tasks**: Users can add new tasks to their to-do list.
- **View Tasks**: Users can view all the tasks in their to-do list.
- **Update Tasks**: Users can edit existing tasks.
- **Delete Tasks**: Users can delete tasks they no longer need.

## Technologies Used

- **Backend**: Flask (Python)
- **Database**: SQLite
- **Frontend**: HTML, CSS, and Bootstrap

## Installation and Setup

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/flask-todo-app.git
   cd flask-todo-app
   ```

2. **Create a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python app.py
   ```

5. **Access the App**:
   Open your web browser and navigate to `http://127.0.0.1:5000`.

## Project Structure

```
flask-todo-app/
├── app.py                # Main application file
├── templates/            # HTML templates
│   ├── base.html         # Base template
│   ├── index.html        # Homepage to view tasks
│   ├── add_task.html     # Form to add a new task
│   ├── edit_task.html    # Form to edit a task
├── static/               # Static files (CSS, JS, images)
│   └── styles.css        # Custom styles
├── models.py             # Database models (if any)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## CRUD Operations

1. **Create**: Add a new task by filling out the form on the add task page.
2. **Read**: View all tasks on the homepage.
3. **Update**: Click the edit button next to a task, modify the details, and save changes.
4. **Delete**: Click the delete button next to a task to remove it.





