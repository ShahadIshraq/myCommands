# myCommands

This is a compilation of the bash files I have created and stored in my root so that I can use them on my terminal.
But for this the folder that holds these files need to be in the path variable. Here is how to do so.

# Find and open .bashrc
.bashrc is in the home directory. so <br>
	*sudo gedit ~/.bashrc*

# Adding the directory to PATH
Add the following line at the end of the file

*export PATH=/myCommands:$PATH *

# Restart your terminal
Restart terminal or simply <br>
	*source ~/.bashrc*
