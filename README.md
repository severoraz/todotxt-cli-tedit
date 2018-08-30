# tedit
A todo.txt-cli shell script extension to edit single tasks in the text editor of your choice.

Listed in the [todo.txt-cli addon directory][1].

## Usage:

    todo tedit ITEM# [BASENAME]

Edit task ITEM# from $TODO_DIR/BASENAME.txt in $EDITOR.
If BASENAME is not given, defaults to 'todo'.

## Parameter conditions: 
 * ITEM# must be an integer
 * BASENAME.txt must exist in $TODO_DIR/"

[1]:https://github.com/todotxt/todo.txt-cli/wiki/Todo.sh-Add-on-Directory
