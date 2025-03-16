# Patient Management System

## Overview
The Patient Management System is a C++ application designed to manage patient records efficiently. It categorizes patients into regular and COVID-19 patients and allows operations such as adding, updating, searching, and deleting patient records.

## Features
- **User Authentication**: Secure login system with username and password.
- **Patient Categorization**:
  - Regular Patients: Includes symptoms, disease name, and city.
  - Corona Patients: Includes immunity level, symptoms, and city.
- **File Handling**:
  - Stores patient data in a text file for persistence.
  - Supports adding, updating, deleting, and searching records.
- **Data Display**:
  - List all patients.
  - Search specific patients by name.
  - Display only corona or regular patients separately.
- **Error Handling**:
  - Uses custom exception handling to validate user input.

## Technologies Used
- **Language**: C++
- **Data Storage**: Text file-based
- **Programming Paradigm**: Object-Oriented Programming (OOP)
- **Development Tools**: Code::Blocks, Visual Studio, g++

## Installation & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/patient-management-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd patient-management-system
   ```
3. Compile the source code:
   ```sh
   g++ main.cpp -o patient_management
   ```
4. Run the application:
   ```sh
   ./patient_management
   ```
5. Log in using the default credentials:
   - **Username**: User
   - **Password**: 1234

## Usage
1. **Add Patient**
   - Choose between Regular or Corona Patient.
   - Enter required details.
2. **Update Patient**
   - Modify patient status and details as needed.
3. **Delete Patient**
   - Remove a patient's record permanently.
4. **Search & Display**
   - View all or specific patient records.
5. **Exit**
   - Quit the application safely.

## UML Diagram
A UML diagram is included in the project documentation to illustrate class relationships and system design.

## Contributors
- **Saad Atif**
- **Qazi Muhammad Usman**
- **Rohan Ahmed**

## License
This project is for educational purposes only. Modify and use it as needed.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Issues
If you encounter any issues, please report them in the GitHub issues section.

