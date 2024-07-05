# To-Do List Application

## Description

The **To-Do List Application** is a simple and intuitive task management system built using Django for the backend and a combination of HTML, CSS (Bootstrap), and JavaScript (jQuery) for the frontend. This application allows users to manage their daily tasks efficiently by adding, updating, and deleting tasks.

## Features

- **Add Tasks**: Users can add new tasks by specifying the task name, due date, and project name.
- **Edit Tasks**: Users can update the due date of tasks directly from the task list.
- **Delete Tasks**: Users can delete tasks that are no longer needed.
- **Mark as Completed**: Users can mark tasks as completed by clicking on the task name, which will toggle a strikethrough effect.
- **Responsive Design**: The application is styled using Bootstrap to ensure it looks good on various devices and screen sizes.

## Project Structure

The project follows a typical Django project structure, with a dedicated `apptodo` application for managing tasks:

### Django Backend:

- **`models.py`**: Defines the database models for tasks.
- **`views.py`**: Handles the logic for displaying, adding, updating, and deleting tasks.
- **`urls.py`**: Maps URLs to the corresponding views.
- **`templates/`**: Contains HTML templates for rendering the frontend.
- **`static/`**: Contains static files like CSS and JavaScript.

### Frontend:

- **`index.html`**: The main HTML file containing the structure of the task list application.
- **`style.css`**: Custom styles to complement Bootstrap.
- **`script.js`**: Custom JavaScript for task management functionalities.

## Usage

- **Adding a Task**: Enter the task name, due date, and project name in the input fields and click "Add Task".
- **Editing a Task**: Change the due date directly in the table to update the task.
- **Deleting a Task**: Click the red `×` icon next to the task name to delete it.
- **Marking as Completed**: Click on the task name to toggle the completed status.
