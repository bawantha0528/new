# Lab 01 – Introduction to UNIX and Vim Editor

## SE1012 – Programming Methodology Semester 1, 2024 (July)

Use VMWare horizon Linux machines for the lab sessions:

1. Use the following link to access VLab: [https://vlab.sliit.lk](https://vlab.sliit.lk)
2. Select “VMWare Horizon HTML Access” out of the two options.
3. Use your SLIIT Email and Password to log into the VLab.
4. Select the Ubuntu virtual PC and double click on it.
5. Stay in the login screen until you are automatically logged in.

### Expected Learning Outcomes

- Use Unix Commands effectively to navigate and manage folders/files.
- Use Vim Editor to create, edit, and save files.

## 1. Introduction to Unix

Unix is a powerful and widely-used operating system known for its stability, flexibility, and versatility. It was developed in the 1960s and 1970s by a group of AT&T Bell Labs researchers, including Ken Thompson and Dennis Ritchie. Unix has become the foundation for various operating systems, including Linux and macOS, and is used in a wide range of applications, from servers and mainframes to personal computers.

One of the key features that make Unix stand out is its command-line interface, which allows users to interact with the system using textual commands. Unix commands offer a fast and efficient way to perform various tasks, ranging from basic file and folder operations to complex system administration tasks.

In this lab, we will explore some fundamental Unix commands to navigate the file system, create and manage files and directories, and manipulate file content. Familiarizing yourself with these commands will provide a solid foundation for working with Unix-based systems, enhance your command-line proficiency, and unlock the full potential of Unix's capabilities.

### 1.1 Basic Unix Commands

| Command | Description | Example |
| ------- | ----------- | ------- |
| pwd | Print working directory | `pwd` |
| cd | Change directory | `cd /home/user/documents` |
| ls | List contents of a directory | `ls` |
| ls -l | List contents with details (long format) | `ls -l` |
| ls -a | List all contents, including hidden files | `ls -a` |
| ls -lh | List contents with details in human-readable size | `ls -lh` |
| cd .. | Move up one level in the directory hierarchy | `cd ..` |
| mkdir | Create a new directory | `mkdir my_folder` |
| rmdir | Remove an empty directory | `rmdir my_folder` |
| rm -r | Remove directory and its contents recursively | `rm -r my_folder` |
| touch | Create an empty file | `touch new_file.txt` |
| mv | Move or rename a file or directory | `mv file1.txt /home/user/documents` |
| cp | Copy files or directories | `cp file1.txt /home/user/documents` |

Explore the Unix commands and examples for more details.

### 1.2 Activity 1

Attempt the below activity using the Terminal.

1. Open the Terminal using the Applications Menu or the keyboard shortcut (Ctrl + Alt + T).
2. Navigate to the Desktop.
3. Create a working directory with your IT number.
4. Inside the directory create 3 Folders: "Activity 1", "Activity 2", and "Activity 1.1".
5. Copy the Activity 1.1 Folder inside the Activity 1 Folder and remove Activity 1.1 from the working directory.

## 2. Introduction to VIM Editor

Vim is a highly customizable and powerful text editor with a steep learning curve, but it becomes extremely efficient once you become familiar with its commands and capabilities. Feel free to practice these commands in Vim to enhance your productivity in text editing tasks.

In the Vim editor, you can switch between the two primary modes, Normal mode and Insert mode, to execute commands and edit the file, respectively. Here's how you can do it:

### 2.1 Switching to Insert Mode

- To enter Insert mode from Normal mode, press one of the following keys:
  - `i`: Start Insert mode before the cursor.
  - `a`: Start Insert mode after the cursor.
  - `A`: Start Insert mode at the end of the current line.
  - `o`: Insert a new line below the current line and start Insert mode.
  - `O`: Insert a new line above the current line and start Insert mode.

### 2.2 Switching to Normal Mode

- To return to Normal mode from Insert mode, press the `Esc` key. This is the most common way to exit Insert mode.

While in Normal mode, you can execute various commands like saving the file, quitting the editor, deleting lines, copying lines, searching, and more. In Insert mode, you can freely edit the text as you would in a typical text editor. The ability to switch between these two modes is one of the distinctive features of Vim, and it allows for efficient and precise text editing using a combination of commands and regular text input. Practice using these modes to become proficient with Vim's editing capabilities.

### Basic Vim Commands

| Command | Description | Example |
| ------- | ----------- | ------- |
| `i` | Start Insert mode (insert before the cursor) | Press `i` |
| `a` | Start Insert mode (insert after the cursor) | Press `a` |
| `A` | Start Insert mode at the end of the line | Press `Shift + A` |
| `o` | Insert a new line below the current line | Press `o` |
| `O` | Insert a new line above the current line | Press `Shift + O` |
| `Esc` | Exit Insert mode and return to Normal mode | Press `Esc` |
| `:w` | Save (write) the file | Press `Esc`, then type `:w` and press `Enter` |
| `:q` | Quit the editor (close the file) | Press `Esc`, then type `:q` and press `Enter` |
| `:wq` or `ZZ` | Save and quit the editor | Press `Esc`, then type `:wq` or `ZZ` and press `Enter` |
| `:q!` | Quit the editor without saving (force quit) | Press `Esc`, then type `:q!` and press `Enter` |
| `dd` | Delete (cut) the current line | Press `dd` |
| `yy` | Copy the current line into the clipboard (yank) | Press `yy` |
| `p` | Paste the contents of the clipboard after the cursor | Press `p` |
| `u` | Undo the last change | Press `u` |
| `Ctrl + r` | Redo the undone change | Press `Ctrl + r` |
| `/search` | Search for a specific word or pattern in the file | Press `/` followed by the search term, then `Enter` |
| `n` | Move to the next occurrence of the search result | Press `n` |
| `N` | Move to the previous occurrence of the search result | Press `Shift + N` |

### Activity 2

Use the Vim Editor to create a file named `lab_notes.txt` under the Activity 2 Folder. Edit the text file by adding the different commands you have used for Questions 1-5 in Activity 1. Save and quit the file.

## 3. Submission

Compile a small report including screenshots showing your work. Rename the report with your IT number and convert it to a PDF file (Example: ITxxxxxxxx.pdf). Upload the PDF file to the given location.
