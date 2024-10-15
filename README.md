# DSA
Phonebook Application 
This is a simple Java-based phonebook application with a graphical user interface (GUI) built using Swing. The application allows users to manage contacts by adding, viewing, searching, updating, and deleting entries. It ensures that duplicate contacts are not allowed and sorts the contact list alphabetically.
________________________________________
Features Overview
•	Add Contact:
Allows users to add new contacts with a name and phone number.
Validates input to ensure both fields are filled and checks for duplicates.
•	View Contacts:
Displays the list of all saved contacts or shows a message if the list is empty.
•	Search Contacts:
Lets users search for contacts by name or phone number, with case-insensitive matching.
Displays matching results or notifies the user if no matches are found.
•	Delete Contact:
Users can select a contact to delete and are prompted to confirm the deletion.
•	Update Contact:
Allows users to edit a selected contact’s name or phone number. Checks for duplicates during the update.
•	Sort Contacts:
Contacts are automatically sorted alphabetically after adding or updating entries.
•	Duplicate Check:
Ensures that no two contacts have the same name or phone number.
________________________________________
Technologies Used
•	Java: Core language used to implement the application logic.
•	Swing: GUI toolkit used to create the user interface.
•	JList and DefaultListModel: Used to display and manage the list of contacts.
________________________________________
System Requirements
•	Java Development Kit (JDK) 8 or higher
•	A Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans) or any text editor with Java support.
________________________________________
How to Install and Run
1.	Download or Clone the Repository
Use the following command to clone the project:
bash
Copy code
git clone <repository-url>
2.	Open the Project in Your IDE
Import the downloaded project into your preferred Java IDE.
3.	Compile and Run the Program
o	Compile the program using your IDE’s build tools.
o	Alternatively, use the terminal:
bash
Copy code
javac Phonebook.java
java phonebook.Phonebook
________________________________________
Application Usage
•	Adding a Contact:
Enter the name and phone number, then click the "Add" button.
•	Viewing Contacts:
Click the "View" button to display all saved contacts.
•	Searching for a Contact:
Enter a search term (name or phone number) in the search field and click the "Search" button.
•	Deleting a Contact:
Select a contact from the list, then click "Delete". Confirm the deletion when prompted.
•	Updating a Contact:
Select a contact and click "Update". Edit the name or phone number in the prompt, and confirm.
________________________________________
Input Validation
•	Name Field: Only letters and spaces are allowed.
•	Phone Field: Only numeric input is accepted.
•	Duplicate Detection: Users cannot add or update a contact with a name or phone number that already exists in the list.
________________________________________
Error Handling
•	Empty Fields: If either the name or phone field is empty during contact creation, an error message is displayed.
•	Duplicate Contacts: If a contact with the same name or phone already exists, the user is notified.
•	Search Failures: If no contacts match the search term, a message will notify the user.
•	Missing Selection: If no contact is selected for deletion or update, the user is prompted to select one.
________________________________________
Possible Improvements
•	Persistence: Save contacts to a file or database to retain data between sessions.
•	Advanced Search: Add support for partial matching or filtering options.
•	UI Enhancements: Improve layout and design for a better user experience.
•	Error Handling: Add more detailed validation and feedback for incorrect inputs.
________________________________________
Contributors
•	Alexsandra Uiras
•	Student Number: 223055298
•	Izane Barman
•	Student Number :224027514
•	Linda Mutileni
•	Student Number: 223138266
•	Hafeni Frans
•	Student Number:224017616
•	Judd-ash John 
•	Student Number224080547
•	Raphael Hatzkin
•	Student Number:224091581
________________________________________
License
This project is open-source and licensed under the MIT License. Feel free to modify and use it as needed.
________________________________________
Thank you for using the Phonebook Application! Let us know if you encounter any issues or have suggestions for improvement.

