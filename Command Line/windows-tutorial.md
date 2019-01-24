# Windows Command Line Tutorial

The command line (or command prompt) is a program in the Windows operating system that lets you create a run custom scripts that can make repetitive tasks or confusing tasks in the Windows filesystem a little easier. While we will be spending more time using Linux systems, it is a good idea to learn the basics of command line on a system that you are a little more familiar with.

### Opening Command Prompt

1.) Click `Start` and type in `run`. Hit `Enter`.
2.) Type `cmd` and hit `Enter`. The Command Prompt will open.

### Navigating the Filesystem

When you open the Command Prompt, you should see something that looks like `C:\Users\hcps`.

This is your location. Think of the command prompt as a vehicle that travels around the filesystem. When the vehicle is "close" to something, you can do things to it with commands.

The first command you will use is `cd`. Type `cd C:\Users\hcps\My Documents` and press `Enter`.

`cd` stands for "change directory". A directory is simply a folder, and `cd` lets you move the Command Prompt to a new directory. Now, you should see that your location has changed to `C:\Users\hcps\My Documents`.

To go one layer up, enter `cd..`. 

To go back to the top of the directory, enter `cd/`.

You can also run programs from the command line. First, navigate to the directory of a file that has a `.exe.` suffix. Then, enter the name of the file (including `.exe`).

### Creating Files

Make a new text file. To do this, enter `echo.>newfile.txt` from your working directory. This will create a new file named `newfile.txt` in your directory.

To add a file with some content, enter `echo Some content >newfile.txt`. Open your file by entering `newfile.txt`.

You can delete your file by entering `del newfile.txt`.

Now, create a new directory inside "My Documents" by entering the following command: `mkdir DirectoryName`. Open "My Documents" in the Explorer and find your new directory.

Rename your file by entering `ren DirectoryName NewName`. Validate your work by viewing the directory in Explorer.


### Analyzing the Filesystem

You can do a number of other things to files in the filesystem using Command Prompt commands. First, navigate to a directory (Downloads is a good one) and then enter `dir`.

You should see a list of all the files in the "Downloads" directory.

You can redirect the output of a command line prompt to a text file to create a log of command prompt activity.

Enter this command: `dir /all > log.txt`. What happened? Validate the output.

### Challenges

Use `ipconfig` to log the network settings to a text file.

Create a Python file (use the `.py` suffix). Include the code `print("This is a Python file.")`. You can run the code by typing `python filename.py`. What is the output?

Look up the command `ping` using your web browser. What does it do? Log the results to a `log.txt` file.

Let me know when you reach this point.


