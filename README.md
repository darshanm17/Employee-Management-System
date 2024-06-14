# Employee Management System

This Java program implements a simple console-based Employee Management System (EMS). It allows users to add, view, update, and remove employee details stored in individual text files.

## Features

- **Add Employee**: Collects and stores employee details in a text file.
- **View Employee**: Displays the details of an employee from their file.
- **Update Employee**: Updates specific details of an employee in their file.
- **Remove Employee**: Deletes an employee's file.
- **Exit**: Exits the EMS program.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine.

### Running the Program

1. **Compile the Program**:
    ```sh
    javac EmployeeInfo.java
    ```

2. **Run the Program**:
    ```sh
    java EmployeeInfo
    ```

### Usage

1. Upon running the program, you will see the main menu with the following options:
    ```
    Press 1 : To Add an Employee Details
    Press 2 : To See an Employee Details 
    Press 3 : To Remove an Employee
    Press 4 : To Update Employee Details
    Press 5 : To Exit the EMS Portal
    ```

2. Enter the number corresponding to your choice and follow the prompts.
3. ![Screenshot (102)](https://github.com/darshanm17/Employee-Management-System/assets/116059183/5203fe8e-3d0c-4b44-8ad9-e87986601338)
![Screenshot (103)](https://github.com/darshanm17/Employee-Management-System/assets/116059183/2b2406fc-97d8-40d5-a1f6-c17ae01fa527)
![Screenshot (105)](https://github.com/darshanm17/Employee-Management-System/assets/116059183/a3e9b031-c0d6-4bf4-a0c7-75fce1e30cf6)
![Screenshot (106)](https://github.com/darshanm17/Employee-Management-System/assets/116059183/03ba7577-5d34-4227-911f-4aa1014bcb5a)


## Classes and Methods

- **`EmployeeInfo`**: The main class that displays the menu and handles user input.
- **`MainMenu`**: Displays the main menu.
- **`Employee_Add`**: Handles adding a new employee.
  - `createFile()`: Prompts for employee details and writes them to a new file.
- **`Employee_Show`**: Handles displaying employee details.
  - `viewFile(String s)`: Reads and displays the contents of an employee's file.
- **`Employee_Remove`**: Handles removing an employee.
  - `removeFile(String ID)`: Deletes the employee's file if it exists.
- **`Employee_Update`**: Handles updating employee details.
  - `updateFile(String s, String o, String n)`: Replaces old detail with new detail in the employee's file.
- **`EmployDetail`**: Holds employee details and provides a method to collect this information.
  - `getInfo()`: Collects employee details from user input.
- **`CodeExit`**: Displays a thank-you message and exits the program.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Created by Darshan M.
