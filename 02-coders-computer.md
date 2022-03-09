# The Coder's Computer - Read 02

1. Choosing a text editor
    1. The main types of text editors are ones that are pre-installed on your computer and third-party options.
    2. Usually, the pre-installed text editors do not have any features that make coding easier. These features include code completion, syntax highlighting, themes, and extensions.
    3. In the end, you may need to try several text editors to find out which one is the best for you. Some software developers my find a feature essential that others can live without.

2. Command line is a text-based interface to the system. In macOS, it’s an app called Terminal.
    1. Basic Navigation
        1. There are often multiple ways to do the same thing. Just use whatever you prefer.
        2. Relative paths are based on where you currently are. The `PWD` (present working directory) command can tell you if you forget. For example, `documents/codefellows` is a relative path in that it assumes that "documents" is a folder in the current location.
        3. Absolute paths are described starting from the root of the file system. For example, `users/username/home/documents/codefellows` is an absolute path becuase it shows how to find the folder starting from the root.
    2. File manipulation
        1. Anything that you do via the GUI can be done in the command line. Creating, copying, moving, and deleting files can all be accomplished with a few commands.
        2. It’s important to remember that there is no undo on the command line, so be aware that changes are permanent.

3. Cheat Sheet
    1. You can press the up arrow key to go back to commands you entered previously rather than typing them again.
    2. Tab can auto-complete the path but also show a list of commands
    3. `touch` - creates a blank file
    4. To replace a file, move (`mv`) one to an existing file name
    5. `rm` = remove
    6. `rm -r` = remove directory with files in it without individually deleting all of the files
    7. man + `[command]`  will show you the instructions and options for that command
