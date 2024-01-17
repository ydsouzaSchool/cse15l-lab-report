Lab Report 1 - Yohann Andrew DSouza
---
## cd command
![Image](/cdCommands.png)
1. `cd` takes you to the home directory
2. `cd *a directory*` as the argument will take you inside the directory, provided the file path exists
3. `cd *a file*` as the argument will give you an error since the purpose of cd is to navigate through directories/ folders, not files.
4. `cd *..*` as the argument takes you one level higher in the directory tree
   On researching more about the `cd` command, I learnt that it stands for change directory, so the above behaviour is rationalized.
---
## ls command
![Image](/lsCommands.png)
1. `ls` lists all directories/ files in the home directory
2. `ls *a directory*` as the argument will list all the directories/ files in the given directory
3. `ls *a file*` as the argument will return the file name if it exists, and will return an error if not
---
## cat command
![Image](/catCommands.png)
1. `cat` just takes input from the user on the CLI and returns it in the same manner
2. `cat *a directory*` as the argument will return an error, since `cat` deals with files, not directories
3. `cat *a file*` as the argument will return the file information, including any encodings for styles unique to the file format

For any of the above commands (cd, ls, cat), if an attempt is made to access a particular file/ directory that doesnt exist, regardless of the command, will result in an error.
