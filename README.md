# VK Groceries
# Console Todo List Application

## Overview

This Java application is a simple command-line Todo List manager. It allows users to add, list, mark as done, and delete tasks. Tasks are persisted to a file, making them available across application runs.

## Features

- Add new tasks
- List all tasks
- Mark tasks as done
- Delete tasks
- Persist tasks to a file
  
**- Testing Your Application**

--**Add Tasks**: Enter commands like add Buy groceries to add new tasks.
--**List Tasks**: Use the list command to view all tasks.
--**Mark Tasks as Done**: Use done 1 to mark the task with ID 1 as done.
--**Delete Tasks**: Use delete 1 to remove the task with ID 1.
--**Exit**: Type exit to end the application.

----**Example Interaction**----

Commands: add [task], list, done [taskID], delete [taskID], exit
Enter command: add Buy groceries
Commands: add [task], list, done [taskID], delete [taskID], exit
Enter command: list
1: Buy groceries
Commands: add [task], list, done [taskID], delete [taskID], exit
Enter command: done 1
Commands: add [task], list, done [taskID], delete [taskID], exit
Enter command: list
1: Buy groceries (done)
Commands: add [task], list, done [taskID], delete [taskID], exit
Enter command: exit
