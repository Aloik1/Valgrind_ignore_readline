# Hello to everyone!
## Are you tired of playing Sherlock Holmes while searching for these pesky leaks in an ocean of readline errors?
Well, good news! I have a solution: **suppession files**
It's not my file, so i would appreciate if you support the creator: [mdabir1203](https://github.com/mdabir1203)
Just Take the file in this repository and add it to the directory with the program you want to run valgrind with
Use **ignore_readline.supp** name for the file
Run valgrind with the next flags:\
`valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes --suppressions=ignore_readline.supp -s ./program`
