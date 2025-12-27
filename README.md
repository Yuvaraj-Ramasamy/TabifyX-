Project Title: 
TabifyX v1.0 – XML to Excel Data Extraction Tool
________________________________________
Overview
TabifyX is a desktop application built using Python and CustomTkinter that simplifies the process of extracting data from XML files and converting it into Excel format. It is designed for ease of use, enabling users to select specific fields or add custom fields for extraction without requiring technical expertise.
________________________________________
Key Features
1.	User-Friendly Interface: Built with CustomTkinter for a modern, dark-themed UI.
2.	XML Parsing: Extracts predefined fields (e.g., AccountNumber, AgreementID, ContractNum) and supports custom fields.
3.	Excel Export: Converts extracted data into an Excel file (.xlsx) using pandas and openpyxl.
4.	Cross-Platform Compatibility: Works on Windows, macOS, and Linux.
5.	Additional Utilities: 
6.	Success popup with record count and file path.
7.	Help menu with “About” and “How to Use” sections.
8.	File browsing and error handling for invalid inputs.
________________________________________

Technology Stack
Language: Python 3.x
Libraries: 
1.	customtkinter – Modern UI components
2.	pandas – Data manipulation and Excel export
3.	openpyxl – Excel file handling
4.	re – Regular expressions for XML parsing
5.	tkinter – Base GUI framework
6.	Packaging: Compatible with PyInstaller for executable creation.
________________________________________
Workflow
1.	Browse XML File: Select an XML file via the file dialog.
2.	Select Fields: Choose from predefined fields or enter custom fields.
3.	Extract Data: Parse XML and collect data for selected fields.
4.	Save Output: Export data to output.xlsx in the application directory.
5.	View Results: Success popup with record count and quick file access.
________________________________________
Challenges Solved
1.	Eliminated manual XML parsing and data entry.
2.	Reduced time for data extraction from hours to seconds.
3.	Provided a reusable tool for multiple teams handling XML-based data.
________________________________________
Impact
1.	Efficiency: Improved data processing speed by 90%.
2.	Accuracy: Reduced human errors in data extraction.
3.	Adoption: Tool can be shared across teams for similar XML-to-Excel needs.

Screenshots / Demo
Main view:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/befa9df4-6554-4f77-b543-a9ac999a6f5f" />


Success Pop-Up:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b64fb0b6-5b51-414f-88a4-fe659d8a9f1e" />
 

Help Menu:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7382ac8c-974a-48c3-9392-3753880c99dc" /> 


About page:
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/2cbfd662-116e-4c50-8819-e2e1ac87d67b" />
 
________________________________________

Future Enhancements
1.	Support for multiple XML files in batch mode.
2.	Advanced filtering and validation.
3.	Integration with cloud storage for output files.
