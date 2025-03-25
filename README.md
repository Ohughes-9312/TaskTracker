# Task Tracker CLI

## Overview
Task Tracker CLI is a command-line application that allows users to track their tasks. You can add tasks, update them, delete them, and mark them as in-progress or done. Tasks are stored locally in a `tasks.json` file.

## Features
- Add tasks
- Update tasks
- Delete tasks
- List tasks (all, done, not done, in progress)
- Mark tasks as in progress or done

## How to Use
1. **Clone the Repository** (if shared on a platform like GitHub):
   ```bash
   git clone <repository-url>
   cd TaskTracker


2. Commands to Run
  - Add a task:
     python task_tracker.py add "New task"

  - List all tasks:
    python task_tracker.py list

  - Update a task:
    python task_tracker.py update 1 "Updated task title"

  - Delete a task:
    python task_tracker.py delete 1

  - Mark a task in progress or done:
    python task_tracker.py mark 1 done
    python task_tracker.py mark 1 progress

REQUIREMENTS
- Python 3.x (no external libraries required)

FILE STRUCTURE
TaskTracker/
│
├── task_tracker.py   # Main program file
├── tasks.json        # Stores tasks data
└── README.md         # Project documentation

Example Output - After adding and listing tasks:
Task 1: Write project documentation - not done
Task 2: Fix bug in task tracker - in progress

License

#### **3. Double-Check Everything**
- Confirm all features work perfectly.
- Test your instructions in the README to ensure they’re accurate and clear.





 
