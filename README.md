Project Title: 
TabifyX v1.0 – XML to Excel Data Extraction Tool
________________________________________
Overview
TabifyX is a desktop application built using Python and CustomTkinter that simplifies the process of extracting data from XML files and converting it into Excel format. It is designed for ease of use, enabling users to select specific fields or add custom fields for extraction without requiring technical expertise.
________________________________________
Key Features
•	User-Friendly Interface: Built with CustomTkinter for a modern, dark-themed UI.
•	XML Parsing: Extracts predefined fields (e.g., AccountNumber, AgreementID, ContractNum) and supports custom fields.
•	Excel Export: Converts extracted data into an Excel file (.xlsx) using pandas and openpyxl.
•	Cross-Platform Compatibility: Works on Windows, macOS, and Linux.
•	Additional Utilities: 
o	Success popup with record count and file path.
o	Help menu with “About” and “How to Use” sections.
o	File browsing and error handling for invalid inputs.
________________________________________

Technology Stack
•	Language: Python 3.x
•	Libraries: 
o	customtkinter – Modern UI components
o	pandas – Data manipulation and Excel export
o	openpyxl – Excel file handling
o	re – Regular expressions for XML parsing
o	tkinter – Base GUI framework
•	Packaging: Compatible with PyInstaller for executable creation.
________________________________________
Workflow
1.	Browse XML File: Select an XML file via the file dialog.
2.	Select Fields: Choose from predefined fields or enter custom fields.
3.	Extract Data: Parse XML and collect data for selected fields.
4.	Save Output: Export data to output.xlsx in the application directory.
5.	View Results: Success popup with record count and quick file access.
________________________________________
Challenges Solved
•	Eliminated manual XML parsing and data entry.
•	Reduced time for data extraction from hours to seconds.
•	Provided a reusable tool for multiple teams handling XML-based data.
________________________________________
Impact
•	Efficiency: Improved data processing speed by 90%.
•	Accuracy: Reduced human errors in data extraction.
•	Adoption: Tool can be shared across teams for similar XML-to-Excel needs.

Screenshots / Demo
Main view:
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/9a72466e-b77b-4ad9-97fd-85098715768a" />


Success Pop-Up:
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/9818365a-c288-4073-8afa-37da5b4d0306" />

 

Help Menu:
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/c31c721f-7b80-4f21-ae05-4df5df644e33" />
 


About page:
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/2cbfd662-116e-4c50-8819-e2e1ac87d67b" />
 
________________________________________

Future Enhancements
•	Support for multiple XML files in batch mode.
•	Advanced filtering and validation.
•	Integration with cloud storage for output files.
