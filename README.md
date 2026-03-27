### Persistent_Task_Manager.py
 
 ## Task Manager CLI 
 A persistent Command Line Task Manager built in Python that allows users to Add, View, Complete, and Delete tasks. Tasks save to a local JSON File, ensuring data is retained between program sessions!

## Features
 * Add new tasks with name, due date, and priority
 * View all tasks with completion status
 * Mark tasks as complete
 * Delete tasks
 * Persistent storage using a JSON File
 * Handles missing or empty tasks lists

## Installation
 1. Clone the repository:
  https://github.com/Misternice203/Persistent_Task_Manager.py.git
 2. Go to Project folder:
    Persistent_Task_Manager
 3. Run the program.
  * Make sure Python 3.14 is installed on your system

## Challenges & Learning:
During this Project I encountered several challenges that helped me grow as a developer:
* Persistent storage with JSON: Learning how to save and load Python data structures to a file.
* Data consistency: I realized that inconsistent key names(e.g. "Completed" vs "completed") could break the program and cause duplicate keys.
* Bug fixing & debugging: Fixing issues like saving the wrong variable(task vs tasks) and handling user input errors.
* Understanding program flow: Ensuring that every change(add, complete, delete) updated the stored file correctly to maintain state of data.
These challenges taught me how to debug effectively(using print statements to find where my dictionary changed to a list), write programs that behave like real world applications.

## Future Improvements 
* Add user input validation (e.g. dates, menu selection)
* Add sorting or filtering by priority or due date
* Add search or search by status functionality
* Transition this CLI into a backend API for web applications

## Technologies Used
* Python 3.14
* Json for persistent data storage
* VS Code
