# Exceptions
Quick explanation on exception errors which usually occur whilst modding the game
Numbered explanations means it could be one of the listed issues.

### ArgumentException
path is a zero-length string, contains only white space, or contains one or more invalid characters as defined by InvalidPathChars.

### ArgumentNullException
path is null.

### DirectoryNotFoundException
The specified path is invalid (for example, it is on an unmapped drive).

### IOException
1.The specified file is in use.

2.There is an open handle on the file, and the operating system is Windows XP or earlier. This open handle can result from enumerating directories and files.

### NotSupportedException
path is in an invalid format.

### PathTooLongException
The specified path, file name, or both exceed the system-defined maximum length.

### UnauthorizedAccessException
1.The caller **does not have the required permission.**
This could mean that a program is also blocking the user from accessing the file, such as `Anti Viruses,and programs that would block suspicous programs/processes/activity`
Other causes would be not having rights aka **lacking admin rights and the likes.** i.e your user or pc has insufficient rights to access/write files and data in anyway. 

2.The file is an executable file that is in use.

3.path is a directory.

4.path specified a read-only file.

