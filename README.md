# To-Do List Application

This is a simple To-Do List application built using Python's Tkinter library.<br> The application allows users to manage their tasks by adding, viewing, and deleting items from a task list. <br>Tasks are stored in a text file so that they persist between sessions.

## Features

- **Add Tasks**: Users can input tasks and add them to the task list.
- **Delete Tasks**: Selected tasks can be removed from the task list.
- **Persistent Storage**: The tasks are saved in `tasklist.txt` and are reloaded when the application starts.
- **Graphical User Interface**: The app uses Tkinter for a simple and intuitive user interface.

## Prerequisites

Ensure that Python is installed on your machine. You can download it from [Python's official website](https://www.python.org/downloads/).

The Tkinter library comes pre-installed with Python, so no additional installations are necessary for this.

## Installation

1. Clone the repository or download the project files.

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory.

    ```bash
    cd to-do-list-app
    ```

3. Ensure that all required image files (`task.png`, `topbar.png`, `dock.png`, `delete.png`) are located in the `Image` directory.

4. Run the Python file.

    ```bash
    python main.py
    ```

## Usage

1. **Adding Tasks**: Type a task into the input field and click the "ADD" button. The task will appear in the list.
2. **Deleting Tasks**: Select a task from the list and click the delete button (trash icon) to remove it.
3. **Task Persistence**: Tasks are saved automatically in `tasklist.txt` and will be loaded when the application is restarted.

## Project Structure

```plaintext
.
├── main.py              # The main Python file that runs the application
├── tasklist.txt         # File where tasks are saved
└── Image/               # Directory for storing icons and images used in the GUI
    ├── task.png
    ├── topbar.png
    ├── dock.png
    └── delete.png
```

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This `README.md` provides an overview of the project, installation instructions, and usage details for potential users. Let me know if you'd like to modify or expand any section.
