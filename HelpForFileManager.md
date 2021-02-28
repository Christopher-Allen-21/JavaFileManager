# Help for File Manager


## Class Descriptions
- **FileManager**: asdf
- **FileOperator**: asdf
- **Console**: Prompts user for String. Saves entered String to a variable. Makes String lowercase and trims whitespace. Returns formatted String.

## Commands in FileManager class

Create object of type FileOperator.(Must pass console object in as a parameter).
`FileOperator myFileOperator = new FileOperator(myConsole);`

- list: Prompts user to enter folder path. Checks whether path exists and is a directory. Returns string of file names if the folder is not empty.
`myFileOperator.list("Desktop/Projects/);`

- info: Prompts user for file/folder path. Returns name, absolute path, relative path, and size of file/folder.
`myFileOperator.info(Desktop/Projects/myFile.txt");`

- mkdir: Prompts user for new folder path. Makes sure a folder with same name does not already exist. Makes sure folder name is appropriate. Creates new folder.
`myFileOperator.mkdir(Desktop/Projects/myNewFolder");`

- rename: Renames file.
`myFileOperator.rename(myFile.txt,myRenamedFile.txt);`

- copy:

- move:

- delete:Prompts user for path of file/folder they want to delete. Checks if file/folder exists and then deletes file/folder.
`myFileOperator.delete("Desktop/Projects/myRenamedFile.txt");`

- quit: Ends program.
`myFileOperator.quit();

