# T&P Helper

## Overview

T&P Helper is a Python-based application designed to automate and simplify the placement process at colleges. This tool is particularly useful for Training and Placement (T&P) coordinators, helping them streamline the workflow and save significant time. The application has been developed into an executable (.exe) file using PyInstaller, making it easy to distribute and use without requiring a Python environment.

## Features

-   **Automated Data Processing**: The application automates the process of gathering and organizing student data for company hiring drives.
-   **Customizable Data Selection**: Coordinators can choose which student details to include in the final output, such as Name, Email, GPA, Phone number, Government ID, Date of Birth, Current Location, Gender and more.
-   **Time Efficiency**: By automating the data handling process, the application manual work.

## How It Works

1. **Data Collection**: When a company requests data of interested students for their hiring drive, students submit their student ID and resume via a Google Form.
2. **Data Files**:
    - **Source Data File (xlsx)**: Contains all student data.
    - **Responses File (xlsx)**: Contains student IDs of interested students and links to their resumes.
3. **Execution**:
    - The application prompts the user to provide the paths to the source data file and the responses file.
    - It then asks which student details should be included in the output (e.g., name, email, GPA, etc.).
    - Based on the selected options, the application fetches the relevant data from the source file and populates the responses file.

## Technologies Used

-   **Python**: Core programming language for the application.
-   **Openpyxl**: Library used for reading and writing Excel files.
-   **PyInstaller**: Tool used to convert the Python script into an executable file.

## Usage Instructions

1. Ensure that the first column of both the source and responses files contains the student ID, and the first row contains headers.
2. File paths should be provided via the terminal, and file names should not contain spaces (use underscores instead).
3. Run the executable and follow the prompts to select the data you wish to include in the output.

## Resources

-   **Executable Application**: [Download the .exe file](https://github.com/aryanbk/TnP_Helper/blob/main/TnP_Helper.exe)
-   **Demo Video**: [Watch the demo](https://drive.google.com/drive/folders/1Nae9cBoBxf0nlgclJUtjk8epJDyWej38)

## Contact

For any questions or support, please contact u19me162@med.svnit.ac.in
