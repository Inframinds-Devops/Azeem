# Linux Commands Tasks

## Task 1: File Operations

1. **Create a File with Your First Name**
   - Command: `touch Abdul.txt`

2. **Add a Few Lines to the File Without Using a Text Editor**
   - Used `echo` command in a script to add lines to the file.

3. **Add a Few More Lines to the File Without Using a Text Editor**
   - Used `echo` command to append additional lines to the file.

4. **Rename the File with Your Last Name**
   - Command: `mv Abdul.txt Azeem.txt`

5. **Print the First 5 Lines of the File**
   - Command: `head -n 5 Azeem.txt`

6. **Print the Last 5 Lines of the File**
   - Command: `tail -n 5 Azeem.txt`

7. **Print Lines 2 to 6 Without Using `sed`**
   - Command: `head -n 6 Azeem.txt | tail -n 5`

## Task 2: File Creation and Process Management

1. **Create a File with First Name in a Text Editor**
   - Created `abdul.txt` in a text editor and did not close the text editor.

2. **Create a File with Last Name in a Text Editor**
   - Created `azeem.txt` in a text editor and did not close the text editor.

3. **List Out Processes Running on the System**
   - Command: `ps aux`

4. **Kill the Process Belonging to the File with First Name Being Opened in the Text Editor**
   - Located the process ID related to `abdul.txt` using `ps aux`.
   - Killed the process using `kill` command.
