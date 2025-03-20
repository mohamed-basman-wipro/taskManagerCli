# taskManagerCli
Task Manager:

Task Manager is a command-line tool that allows users to manage tasks by adding, listing, and deleting them. It is designed as a Python wheel package, making it easy to install and distribute.

Features:

    Add new tasks with description, due date, and category.
    List all tasks sorted by due date.
    Delete specific tasks by ID.
    Delete all tasks at once.
    Tasks are stored persistently in a JSON file.
    Simple command-line interface for interaction.

Folder Structure:

Task_Manager/
├── dist/                   # Contains built wheel and sdist files
├── task_manager/           # Main package folder
│   ├── __init__.py
│   ├── cli.py              # CLI interface logic
│   ├── task_manager.py     # Core task manager functions
│   └── tasks.json          # Task database
├── pyproject.toml          # Build configuration
└── README.md               # Project description (this file)
