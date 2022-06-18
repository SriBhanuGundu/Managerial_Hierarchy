# Managerial_Hierarchy
## Introduction:
  Every company or organization requires data base to add or remove the particular employee content and update the changes whenever required. So, python with oops concepts implemented managerial hierarchy without using in built libraries of python.
  Implemented with multi level inheritance of claases and objects with advanced trees for assigning hierarchy to the employees.
  
## Implementation:
Implementing the HR System in an organization comprising of two departments "IT" and "HR". The implementation is based on the trees using classes and objects with the concept of "Inheritance". For this purpose, created six classes namely: Department, which is containing information about Departments and can be extended and currently I am considering two departments of "HR" And "IT". StaffMembers, which contains information about employee details like employee number, name, zipcode, birthday, hiring date, this class is implemented with inheritence concept collecting data from Department into StaffMembers class. Developers, which contains information about employees who are sub ordinates under managers in particular department. Managers, which contains the information about the manager under whom sub ordinates are present. Administrator, which contains the information about the employees as sub ordinates under him that includes employees and managers for particular departments. All these classes are implemented with "Inheritance", Developers, Managers and Administrator classes have multi level inheritence.

![image](https://user-images.githubusercontent.com/95875120/174456436-f21ab035-4225-4c02-a389-3570a4ecb81f.png)

## Conclusion:
Employee HR Organization table is created with provision of adding, removing, making changes, providing subordinates under managers using Employee hierarchy in which Administrator is the main head followed by managers and Employees in various departments. Even the data in the table can be modified and new employee can be added with the methods, classes and objects implemented. Care is taken to reduce the space complexity and time complexity by using concept of list of dictionaries and limited to maximum of one for loop.

Overall, in this project, I used list, dictionary, lambda function, filter, append inbuilt methods, imported datetime library, classes and objects, method callings, time complexities, sorting techniques, testing code with unit test cases that were learnt in the class.
  
  
