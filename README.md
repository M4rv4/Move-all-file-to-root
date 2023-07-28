# File Mover Script with GUI

<p>The File Mover Script is a Python program for moving files from subfolders to a given root folder. The script also handles duplicate filenames by suffixing them with numbers in order of occurrence. Additionally, it performs the deletion of empty subfolders after the file-moving operation. The program utilizes the tkinter library for GUI development and the logging module for tracking the progress of the operation.</p>

## Features:

- Move Files: The script enables the user to select a root folder through the GUI. It then recursively moves all files from subfolders to the root folder.
- Handle Duplicate Filenames: When a file with the same name exists in the destination folder, the script adds a numeric suffix to the filename until a unique filename is found. For example, if two files named "example.txt" exist, they will be moved as "example.txt" and "example_1.txt."
- Delete Empty Subfolders: After moving the files, the script identifies and deletes empty subfolders in the root folder.
- Logging: The script logs the details of the file-moving process, including successful moves, failed moves, and the deletion of empty subfolders. It stores the log information in a file named "file_mover.log" in the same directory as the script.

![example](/assets/img/z21dv59a234.png "example")
## How to Use:

Install [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) first. 

`pip3 install customtkinter`

Start: Run the script with run.bat or

`python main.py.`

<ol>
<li>Click the "Select Root Folder" button to choose the destination root folder for moving the files.</li>
<li>The script will move all the files from subfolders to the root folder, handling duplicates and deleting empty subfolders.</li>
<li>The GUI will display the result of the operation, indicating the number of files moved successfully and the number of files that failed to move.</li>
<li>The "Clear Log" button can be used to clear the log file and start logging afresh.</li>
</ol>

Please ensure to use this script with caution, especially when performing file operations. Always make sure to have a backup of your data before running any file-moving or file-deletion operations.

## Special Thanks:
[CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)