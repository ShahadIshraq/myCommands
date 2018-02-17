# My custom bash commands

This is a compilation of the bash files I have created and stored in my root so that I can use them on my terminal.<br>
* The **Creating Launcher** directory has directions on creating custome launcher. Came handy in making a one click launcher for my XAMPP server.<br>
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

## License

No license whatsoever. Use at your own risk.

## Acknowledgments

* [Google](www.google.com)
* [UNIX stackexchange](unix.stackexchange.com)
* [askubuntu](askubuntu.com)


