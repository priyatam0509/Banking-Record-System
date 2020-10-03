# Banking-Record-System
This banking record system project in C++ is a console application developed without the use of graphics component. It is more of a database project in C++, and is built using the language’s file handling mechanism. It is suitable for beginners who want to learn how to add, edit, search, delete or modify records in a file, and how to use file as database overall.

File handling has been effectively used for each feature of this project. Here, I am going to describe these features in brief:-

1. Add Record: For this feature void read_data() function has been used to add banking record into the file. It asks for information such as account number, first name, last name and balance to be entered. 

2 .Show/List Data: With the information provided in add record, the void show_data() function in this banking record system project in C++ show the record corresponding to a particular account number, first name and last name. Current balance of the account holder is displayed. 

3. Search Record: When the function for this feature is first executed, it shows the total records in the file, and the user can then search by record number. If the record searched for is not found, the banking record system project in C++ displays the message – “Error in opening! File Not Found!!”

 4.Edit Record: This works in similar manner to the Search feature. When the function for Edit Record is first executed, it shows the total records in the file, and the user can edit the information by providing record number. Then, the C++ project shows all the data in that record, and the user can enter any data to modify. If the record to be edited for is not found, it displays the message – “Error in opening! File Not Found!!” 

5.Delete Record: First of all, when the function of this feature is executed, it shows all the records in the file, and the user can enter the record number to delete. If the record was not found, this banking record system project in C++ displays the message – “Error in opening! File Not Found!!”
