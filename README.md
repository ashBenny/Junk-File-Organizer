# Junk-File-Organizer ( Python )

## Objective

When the user’s machine (PC) is full of unorganized files (Junk files), that will be hard to find out some particular files. 
There comes the importance of organizing junk files in a machine. With an organized machine, user can easily find out the files 
instead of hunting through folders and sub-folders. This is a project to make that task easy.

## Features

Organize by file Extension :

By using organize_ext function in the code, files will be organized with reference to the file 
format (extension). A dictionary is created with file category as ‘keys’ and file extensions as 
‘values’. While functioning, a new folder will be created named ‘Organized files’ and the files will 
be moved to inside of that folder within their respective file category folders

Organize by file Size :

By using organize_size function in the code, files will be organized with reference to the size of 
the file. While functioning, a new folder will be created named ‘Organized files’. The files will be 
moved ‘Small size’, ‘Mid size’ and ‘Large size’ within the ‘Organized files’

 Organize by Month, Year :
 
By using organize_month function in the code, files will be organized with reference to the 
month & year the file is created. While functioning, a new folder will be created named 
‘Organized files’ and the files will arranged based on their month & year.

## How to run

To organize by extension : python <filename.py> --org ext
To organize by size : python <filename.py> --org size
To organize by month & Year : python <filename.py> --org month 

User defined path : python <filename.py> --path “ <path of the files to be organized> “

