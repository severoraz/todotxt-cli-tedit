# tedit
A todotxt-cli extension to edit single tasks in the text editor of your choice.

Usage:

    todo tedit ITEM# [BASENAME]

Edit task ITEM# from $TODO_DIR/BASENAME.txt in $EDITOR.
If BASENAME is not given, defaults to 'todo'.

## Parameter conditions: 
 * ITEM# must be an integer
 * BASENAME.txt must exist in $TODO_DIR/"
