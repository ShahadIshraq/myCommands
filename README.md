# My custom bash commands

This is a compilation of the bash files I have created and stored in my root so that I can use them on my terminal.
But for this the folder that holds these files need to be in the path variable. Here is how to do so.

## Getting Started

To use this commands in the terminal you need to add the directory to the PATH variable. Lets say we are saving this files in /myCommand/ directory.

### Find and open .bashrc
.bashrc is in the home directory. so

```
sudo gedit ~/.bashrc
```

### Add the directory to PATH
Add the following line at the end of the file

```
export PATH=/myCommands:$PATH
```

### Restart your terminal
Restart terminal or simply

```
	source ~/.bashrc
```


