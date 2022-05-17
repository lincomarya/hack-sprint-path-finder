# Hack Sprint Path Finder

**Hack Sprint Path Finder** is a Hackathon organized by **Lincom Arya** where you can explore linux by solving the Path Finder Puzzle.

## How to Get Started

Open **Command Prompt / PowerShell** on your Windows Machine.

Type **```ssh lincomarya@3.111.209.97```** and press enter.

Type **yes** and press enter.

Password is **```arya@2020```**

Type **```ls```** command to list the file for first level's instructions and proceed further.

## How to Submit answer

Make a document named **```answer.md```** explaining how you approached each level with the help of commands.

The Document should contain your **name**, **year**, **branch**.

- Fork the repo - **https://github.com/lincomarya/hack-sprint-path-finder**
- Clone the repo by using this command : **```git clone [url of the forked repo]```**
- Create a new branch with your name by using this command : **```git checkout -b [your name]```**
- Create **answer.md** file.
- Add your files to the staging area by using **```git add . ```**
- Commit your code : **```git commit -m [commit message]```**
- Push your code by using : **```git push -u origin [branch]```**
- Create new **pull request** on **https://github.com/lincomarya/hack-sprint-path-finder/pulls**

## Note

Your submission won't be counted until you create a **pull request**.

**Don't share your answer with anyone**.

We will be checking every pull request , contestant will be disqualified if involved in **plagiarization**.

## Commands to be Used

**```pwd```** - displays the present working directory where you currently are.

**```ls```** - This command will list the contents of a directory.

**```ls -la```** - This command will list all the content of a directory incliuding the hidden files and directories.

**```mkdir [dir_name]```** - This command will create a new directory, provided it doesn't exists.

**```rmdir [dir_name]```** - This command will remove/delete an existing directory, provided it is empty.

**```cd [directory_name]```** - This command is used to change directory.

**```touch [file_name]```** - This command will creates a new file.

**```rm [file_name]```** - This command will delete a file.

**```rm -f [file_name]```** - In order to delete a file forcefully.

**```rm -r [dir_name]```** - In order to delete a directory containing multiple files.

**```rm -rf [dir_name]```** - In order to delete a directory forcefully containing multiple files.

**```cp [file1_name] [file2_name]```** - Copying contents of files , 
This command copies the content of file file1 into file file2. If file file2 doesn't exists then it is created. If it exists then its content is overwritten.

**```cp -r [dir1_name] [dir2_name]```** - In order to copy one directory to another directory, following can be done.

**```mv [current_name] [new_name]```** - Renaming files and directories
command to rename files and directories.

**```mv /[dir1]/[file_name] /[dir2]/```** - Moving files and directories
command to move files and directories , 
It’s done in the following manner.

**```cat [filename]```** - Viewing the contents of the files
This command prints all the content of a file.

**```head [file_name]```** - In order to print the first 10 lines of a files.

**```tail [filename]```** - In order to print the last 10 lines of a files.

**```zip [file1name] [file2name] [file3name]```** - This command can be used to zip files in an directory.

**```zip -d [zipped_filename] [file1name]```** - In order to remove a file from the .zip file.

**```zip -u [zipped_filename] [file2name]```** - Inorder to update the existing .zip file.

**```zip -m [zipped_filename] [filename]```** - In order to move specific files to an the zip file. That means that after adding the files, they will be deleted from their original directories.

**```zip -x [zipped_filename] [filename]```** - In Order to exclude unwanted files.

**```unzip [zipped_filename.zip]```** - The following command can be used to unzip files.

**```unzip [zipped_filename] -d [dir_path]```** - In order to unzip to a different directory.

**```unzip -P [password] [zipped_filename]```** - In order to unzip an password protected file.
