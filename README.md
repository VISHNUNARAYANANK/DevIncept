# DevIncept
This is a group Project.
## File Manager in Python
A file manager is a computer program that provides a user interface to manage files. and folders.
The most common operations perfomed on files or group of files include **Creating, opening,renaming,moving,deleting, etc.**
## File Manager in Python
A file nanager is a computer program that provides a user interface to manage files. and folders.
The most common operations perfomed on files or group of files include **Creating, opening,renaming,moving,deleting, etc.**
* ## Steps to bulild File Manager in Python
Our goal in this project is to come with our file manager.
## Step 1: Importing all required modules
* We will import the following modules:
* **Tkinter:** It provides wide API for GUI functionlities.
* **Shutil:** This module offers a number of high-level operations on files and collection of files.
* **Os:** utility module for OS interaction in programs.
* **easygui:** It allows us to select any file from the system.
* **Filedialog:** This libraay is used for folder selection.
* **Imageio:** This is used to read the chosen file.
## Step 2: Defining functionalities
In this step, we will define all the functions which will be linked afterward to different buttons
* **Opening a file box:** It opens the file box,i.e the pop-up box to choose the file from the device, which opens every time we run the code. 
fileopenbox() is the method in easyGUI module which returns the path of the chosen file as a string.
 * **Opening a file:** Opening a file when Open a file button is clicked.
 * **copying a file:** Copying a file when copy a file button is clicked.file copying is the creation of a new file which has the same content as an existing file.
* **Deleting a file:** Deleting a file when Delete a file button is clicked.
 Select the files and folders you want to delete.
 Click or tap the Delete button arrow on the Home tab, and then click delete.
* **Renaming a file:** Select your file or folder, and then click on the "Rename" button that will appear.
* **Moving a file:** The "Move" button will also open a small window, that looks almost exactly like the "Copy".
Click on the "Select Destination" box, to see a list of locations, and click on the "Move" button to move the file.
* **Making a folder**
Making a file when Make a folder button is clicked.
* **Listing files in a folder**
Listing files in a folder when List all files in a directory button is clicked.
* **Building File Manager UI using Tkinter:**
Tkinter has two types of layout managers, grid and pack. For layout simplicity, we use a grid layout manager. Simply, using grid, we place every button in a single column.

**Label()** is used to place text label in the root window, with defined font, font size, and color. Row and column are also specified at the end.
**Button()** function placed in root window with text specified as text=”..” . The next parameter, “command” specifies the function which gets executed whenever a button is clicked. Please note, the function is specified without brackets in the statement. Similar to label, in every grid widget, we can specify row and column. To place the buttons one below the other, we specify the same column number, but change the row according to our need.
## File Manger Output:







 

