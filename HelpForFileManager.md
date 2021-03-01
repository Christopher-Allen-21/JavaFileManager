# Help for File Manager


## Class Descriptions
- **FileManager**: Prompts user for a command. Processes the command if the command is valid.
- **FileOperator**: Used to create FileOperator object. Methods are commands used for file management.
- **Console**: Used to create Console object that prompts user for String, saves the entered String to a variable, makes the String lowercase, trims whitespace, and returns the formatted String.

## Commands in FileManager class

Create object of type FileOperator by passing in a Console object.\
`FileOperator myFileOperator = new FileOperator(myConsole);`

- *list*: Prompts user to enter folder path. Checks whether path exists and is a directory. Returns string of file names if the folder is not empty.\
`myFileOperator.list("Desktop/Projects/);`

- *info*: Prompts user for file/folder path. Returns name, absolute path, relative path, and size of file/folder.\
`myFileOperator.info(Desktop/Projects/myFile.txt");`

- *mkdir*: Prompts user for new folder path. Makes sure a folder with same name does not already exist. Makes sure folder name is appropriate. Creates new folder.\
`myFileOperator.mkdir(Desktop/Projects/myNewFolder");`

- *rename*: Prompts user for path of file/folder to rename. Renames file/folder if it exists.\
`myFileOperator.rename(myFile.txt,myRenamedFile.txt);`

- *copy*: Prompts user for file/folder to copy. Copies that file/folder if it exists.\
`myFileOperator.copy("Desktop/Projects/myFile.txt");`

- *move*:Prompts user for path of file/folder to copy and move and destination path. Moves the file/folder.\
`myFileOperator.move("Desktop/Projects/myFile.txt,Desktop/");`

- *delete*:Prompts user for path of file/folder they want to delete. Checks if file/folder exists and then deletes file/folder.\
`myFileOperator.delete("Desktop/Projects/myRenamedFile.txt");`

- *quit*: Ends program.\
`myFileOperator.quit();`

