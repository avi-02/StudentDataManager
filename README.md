## StudentDataManager  

Student Data Manager
Overview
The Student Data Manager is a console-based program designed for efficiently managing official student data. It allows users to store and manipulate records such as student ID, name, course, department, and phone number. The program writes data into a CSV (Comma Separated Values) file format, which can be easily opened and edited using spreadsheet software like Google Sheets, Microsoft Excel, or LibreOffice Calc.

###Why CSV?
CSV files offer exceptional portability and ease of sharing. They enable data to be viewed and edited across different platforms without requiring the original Student Manager Program, making it convenient for collaboration and data exchange.

###Features
Add Student Records: Easily add new student records with built-in duplicate ID prevention.
View All Records: Display all stored records in a clear and organized table format.
Update Records: Modify existing student records, with the option to cancel changes during the update process.
Delete Records: Remove specific student records based on their ID.
Search: Quickly locate and view details of any student record by their ID.
Compatibility Note
This program utilizes the unistd.h library, which includes functions like sleep() and system("clear"), specifically designed for Unix/Linux-based operating systems. Detailed instructions for adapting the program to other operating systems, such as Windows, will be provided soon.

### Few screenshots of the program running in terminal-
![Admin's Menu](screenshots/admin_menu.png "Admin's Menu")
![Add Record]([screenshots/add_record.png "Add Record"](https://github.com/avi-02/StudentDataManager/blob/main/add_record.png))
![View Records](screenshots/view_record.png "View Records")
![Delete Record](screenshots/delete_record.png "Delete Record")

### To get and run this program, run these commands in your terminal:

1.  git clone git@github.com:Bishnukt/Student_Data_Manager.git
1.  cd Student_Data_Manager
1.  g++ -o sdm sdm.cpp admin.cpp load.cpp
1.  ./sdm
