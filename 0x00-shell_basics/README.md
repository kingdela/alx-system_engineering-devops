The *0-current_working_directory* file prints the absolute path name of the current working directory.
The *1-listit* file displays the contents list of your current directory.
The *2-bring_me_home* file changes the working directory o the user's home directory
The *3-listfiles* file displays current directory contents in a long format.
The *4-listmorefiles* file display current directory contents, including hidden files (starting with .)
The *5-listfilesdigitonly* file display current directory contents.
The *6-firstdirectory* file creates a directory named __my_first_directory__ in the __/tmp/__ directory.
The *7-movethatfile* file move the file __betty__ from __/tmp/__ to __/tmp/my_first_directory__.
The *8-firstdelete* file delete the file __betty__.
The *9-firstdirdeletion* file delete the directory __my_first_directory__ that is in the __/tmp__ directory.
The *10-back* file changes the working directory to the previous one.
The *11-lists* file  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the __/boot__ directory (in this order), in long format.
The *12-file_type* file prints the type of the file named __iamafile__. The file __iamafile__ will be in the __/tmp__ directory when we will run your script.
*13-symbolic_link* - Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
*14-copy_html* - Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
*100-lets_move* - Creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
*101-clean_emacs* - Creates a script that deletes all files in the current working directory that end with the character ~.
*102-tree* - Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
*103-commas* - Write a command that lists all the files and directories of the current directory, separated by commas (,).
*school.mgc* - Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.