# To-Do List App

The to-do list app allows users to add tasks, view existing tasks, and delete tasks from the list. It runs on the command-line interface (CLI) and provides an easy way to manage your daily tasks.

## Features

- Add new tasks: Users can add new tasks to the to-do list.
- View tasks: Users can view all the tasks in the to-do list.
- Delete tasks: Users can remove tasks from the to-do list.
- User-friendly interface: The app presents a simple menu-driven interface for easy interaction.

## Technologies Used

- Python

## How to Use

1. Clone or download the `todo.py` file to your local machine.

2. Make sure you have Python installed on your computer.

3. Open a terminal or command prompt and navigate to the directory where `todo.py` is located.

4. Run the following command to start the To-Do List App:

   ```
   python todo.py
   ```

5. The app will display a menu with the following options:

   ```
   Menu:
   1. Add Task
   2. View Tasks
   3. Delete Task
   4. Exit
   ```

6. Choose the desired action by entering the corresponding number.

- To add a task, select option `1` and follow the instructions to enter the task details.
- To view existing tasks, select option `2`, and the app will display the current tasks.
- To delete a task, select option `3`, and the app will prompt you to enter the task number to delete.

7. To exit the app, select option `4`, and the program will terminate.

## Example

Here's an example of how the app works:

```
Menu:
1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter your choice: 1
Enter the task: Buy groceries
Task added successfully!

Menu:
1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter your choice: 1
Enter the task: Finish report
Task added successfully!

Menu:
1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter your choice: 2
Tasks:
1. Buy groceries
2. Finish report

Menu:
1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter your choice: 3
Tasks:
1. Buy groceries
2. Finish report
Enter the task number to delete: 1
Task deleted successfully!

Menu:
1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter your choice: 2
Tasks:
1. Finish report

Menu:
1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter your choice: 4
Exiting program.
```

## License

This project is licensed under the [MIT License](LICENSE).
