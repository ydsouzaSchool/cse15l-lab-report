Lab Report 1 - Yohann Andrew DSouza
---
## Please note: the order of the explanation and the order of the commands in the screenshots may differ. Everything is explained with reference to the images though.

---

[comment]: <> (Include the working directory at each point, and explain whether or not it is an error)
## cd command
![Image](/cdCommands.png)
Working 
1. `cd` takes you to the home directory. Working directory at this time was `/Users/yohanndsouza/Downloads`, `cd` took me back to `/Users/yohanndsouza`. No error here, this is the normal expected output.
   
2. `cd *a directory*` as the argument will take you inside the directory, provided the file path exists. Working directory at this time was /Users/yohanndsouza. `cd downloads` took me to `/Users/yohanndsouza/Downloads`. No error here, this is the normal expected output from this command. `cd *directory that doesn't exist` yields an error though, which is expected, since you cannot enter a directory that doesn't exist.
   
3. `cd *a file*` as the argument will give you an error since the purpose of cd is to navigate through directories/ folders, not files. Working directory was `/Users/yohanndsouza`. the `cd *a file*` command in this context accomplishes nothing as explained earlier.
   
4. `cd *..*` as the argument takes you one level higher in the directory tree. Working directory was `/Users/yohanndsouza/downloads`. After using `cd ..`, it took as to the directory one level higher, `/Users/yohanndsouza`. No error here, expected behaviour.
   On researching more about the `cd` command, I learnt that it stands for change directory, so the above behaviour is rationalized.

--- 

## ls command
![Image](/lsCommands.png)

1. `ls` lists all directories/ files in the home directory. Working directory at this time was `/Users/yohanndsouza`. `ls` here displayed all directories and files within `Users/yohanndsouza`. This is the normal expected output from this command.

2. `ls *a directory*` as the argument will list all the directories/ files in the given directory. Working directory was `Users/yohanndsouza`. On running `ls documents`, we can see all the directories/ files in `Users/yohanndsouza/Documents`, which is the normal expected output from this command.
   
3. `ls *a file*` as the argument will return the file name if it exists, and will return an error if not. This is once again the normal expected behaviour. running `ls joemama.pdf` under the working directory `Users/yohanndsouza/Documents` returns an error because it doesn't exist. running `ls CoverLetter_YohannDsouza.pages` under the same working directory returns the file name, since it does exist. 

---

## cat command
![Image](/catCommands.png)
1. `cat` just takes input from the user on the CLI and returns it in the same manner
2. `cat *a directory*` as the argument will return an error, since `cat` deals with files, not directories
3. `cat *a file*` as the argument will return the file information, including any encodings for styles unique to the file format

For any of the above commands (cd, ls, cat), if an attempt is made to access a particular file/ directory that doesnt exist, regardless of the command, will result in an error.
