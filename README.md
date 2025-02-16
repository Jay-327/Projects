# Projects
This is a simple Contact Management System built using Python and Tkinter for the graphical user interface (GUI) along with SQLite3 for database operations.

Features

Add new contacts (Firstname, Lastname, Gender, Age, Address, Contact Number)

Update existing contact information

Delete selected contacts

View contact list in a table format

Prerequisites

Ensure you have Python installed on your system (Python 3.x is recommended).

Modules Used

The application uses the following built-in Python modules:

tkinter – Used for creating the GUI.

sqlite3 – Used for handling SQLite database operations.

tkinter.ttk – Provides advanced GUI widgets like Treeview.

tkinter.messagebox – Used for displaying message boxes like warnings and confirmations.

How It Works

Main Components:

Database Creation:

A database named pythontut.db is created (if not already existing) with a table called member.

Columns: mem_id, firstname, lastname, gender, age, address, contact.

Adding a Contact:

Click on the "+ ADD NEW" button.

Fill in the form with contact details.

Click on the "Save" button to submit the data.

Updating a Contact:

Double-click on a contact entry in the list.

Modify the fields as required.

Click on the "Update" button to save the changes.

Deleting a Contact:

Select a contact entry from the list.

Click on the "DELETE" button.

Display Table:

The table is displayed using Treeview with horizontal and vertical scrollbars.

Displays columns for Member ID, Firstname, Lastname, Gender, Age, Address, and Contact.
