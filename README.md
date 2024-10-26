Description: Task tracker CLI is a simple Command Line Interface (CLI) used to track what you need to do, what you have done, and what you are currently working on.

The application can run from the command line, accept user actions and inputs as arguments, and store the tasks in a JSON file. The user should be able to:

- Add, Update, and Delete tasks 
- Mark a task as in progress or done 
- List all tasks 
- List all tasks that are done 
- List all tasks that are not done 
- List all tasks that are in progress

Valid commands: 'add', 'update', 'delete', 'mark-in-progress', 'mark-done', 'list'

Example
The list of commands and their usage is given below:

# Adding a new task
task-cli add "Buy groceries"
# Output: Task added successfully (ID: 1)

# Updating and deleting tasks
task-cli update 1 "Buy groceries and cook dinner"
task-cli delete 1

# Marking a task as in progress or done
task-cli mark-in-progress 1
task-cli mark-done 1

# Listing all tasks
task-cli list

# Listing tasks by status
task-cli list done
task-cli list todo
task-cli list in-progress