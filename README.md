# Process Writeup

## Name: Farzona K 
## Course: SEP 10
## Period: 8
## Concept: Command Line Interface

### Section: Context 
We are now in Unit 2, which focuses on GitHub, Git, and the command line. So far, we have primarily discussed the command line. The command line was essentially about using code to create folders and arrange them. It was easy to understand because the lessons were straightforward and not overly complex. 

#### Basics of Command Line Interface:
* `↑` (up arrow): Scrolls through the command history (previous commands entered in the terminal).
* **Tab**: Auto-completes file or directory names (based on what's available in the current directory).
* `clear`: Clears the terminal screen, without deleting anything.
* `..`: Refers to the parent directory (one level up).
* **~**: Represents the home directory of the current user.
* **/**: Represents the root directory of the filesystem.
* `pwd`: Prints the current working directory (shows the full path).
* `ls`: Lists files and directories in the current directory.
* `cd`: Changes the current directory to the specified directory.
* `mkdir`: Creates a new directory.
* `rmdir`: Removes an empty directory.
* `touch`: Creates a new, empty file or updates the timestamp of an existing file.
* `rm`: Removes (deletes) a file.
* `rm -rf`: Forcefully removes a directory and its contents, without confirmation prompts.
* `mv` (to rename): Renames a file or directory.
* `mv` (to move): Moves a file or directory to a new location.

#### Process: 

Our teacher taught us the command line by talking through everything while we took notes. He gave a lot of examples to help us understand how each command worked. To make sure we really got it, he had us practice using websites like [JSCLI](https://hstatsep.github.io/jscli/) This website let us try out the commands on our own and gave us different exercises to help us get the hang of things. The more we practiced, the easier it got to understand how to use the command line.

We practiced using the command line by creating and managing different folders. First, we used the `mkdir` command to create the folders, then we tried out other commands to interact with them. We used `cd` to change between directories, and `..` to go up one level to the parent directory. The `~` symbol helped us quickly go to the home directory. We used `touch` to create files inside the folders, and `mv` to move files around or rename them. If we wanted to delete files, we used `rm`, and to completely remove a folder and everything inside it, we used `rm -rf`. To check where we were, we used `pwd` to see our current directory, and ls to list what was in a folder and `clear` to wipe the screen clean. Practicing all these commands helped us get comfortable with managing files and folders and made us more confident using the command line.

Some examples we had to practice with on JSCLI: 


![image](https://github.com/user-attachments/assets/ef6f92f5-69fc-4b46-a805-f6f5a03200df)

and

![image](https://github.com/user-attachments/assets/3868140f-d784-403f-b5cf-ce82243bc2e4)
![image](https://github.com/user-attachments/assets/49fa0580-9817-41bb-9b92-ca3af71df4ae)

### Challenge 1
A challenge I faced while learning the command line was understanding the difference between the `mv` command used for renaming and moving files. At first, I thought these two actions were completely separate, and I wasn’t sure how to use them properly in different situations. For example, when I was trying to rename a file, I used the `mv` command, but then I wondered why it also worked for moving files between directories. I was confused about how both operations could be done using the same command.

The breakthrough came when my teacher explained it more clearly. He showed us that the mv command is versatile — it can both move and rename files, depending on how it's used. If you're moving a file, you simply specify the new location after the file name, like this:

``` bash
mv myfile.txt /newfolder/
```

But if you're renaming it, you provide the new file name in the same location:

``` bash
mv oldname.txt newname.txt
```

One important distinction I learned was that when moving a file or folder, the destination (the folder or directory you're moving it into) has to already exist. On the other hand, when renaming a file, you don’t need to worry about whether the new name already exists — it just changes the file’s name in the same location. Once I understood this, it clicked! The mv command works for both tasks, but the context (whether you’re giving it a new path or a new name) determines whether it's moving or renaming. It made a lot more sense, and I felt much more comfortable using the command line after practicing this a few times. It really helped me understand the power of the mv command and how to use it efficiently in different situations.

### Challenge 2 
A challenge I faced while learning the command line happened during a quiz question about the command `cd ...` I knew what the command did, it moves you to the parent directory, but when I took the quiz, I didn’t fully notice the `..` part. I just saw `cd`, and since I knew `cd` is used to change directories, I assumed the question was asking about moving to the child directory, which is what I thought cd did. I got so focused on the idea of "change directory" that I missed the `..` and mistakenly chose the wrong answer.

The quiz question was: "What does cd .. mean?"

And the options were:


