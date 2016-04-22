# Notes1.0

Notes1.0 is a programme that allows the user to keep a notebook available from the command line.
The user can create, search and read their notes as well as delete specific notes or lines. 


## Installation:

##### 1. Save the file notes1.0 in the directory where you keep your scripts. If you don't have such a directory, create one.

##### 2. Register the location of your directory on .bashrc so that the shell can call notes1.0 directly, just like other programs, without having to specify the whole path every time.

###### Substitute DIRECTORY by the complete location of the directory in which notes1.0 is located.
###### $ echo "export PATH=\"DIRECTORY:\$PATH\"" >> ~/.bashrc

##### 3. Set the permissions for the script file to executable (authorize the shell to execute notes1.0 as a program).

###### Substitute COMPLETE_PATH_TO_SCRIPT by the complete location of notes1.0.
###### $ chmod 755 COMPLETE_PATH_TO_SCRIPT 

##### 4. Restart your terminal.

###### notes1.0 is now part of your shell/bash.


## Usage

##### $ notes1.0 [arguments] "Your notes within quotes"
###### In the absence of arguments, the note will be appended to the last created note.

##### Reading the instructions:

$ notes1.0

##### Creating a new note:

$ notes1.0 -n "My first note."

##### Adding to the last note:

$ notes1.0 "Addition to last note."

##### Creating a second note:

$ notes1.0 -n "My second note."

##### Reading notes:

$ notes1.0 -r

##### Searching for a note:

$ notes1.0 -s "first"
