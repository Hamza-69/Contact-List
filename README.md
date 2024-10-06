![Showcase](https://github.com/Hamza-69/Contact-Manager/blob/main/ezgif-2-b8d5db5c31.gif)

# Contact Manager

**Contact Manager** is a Python-based application that allows users to store, manage, and retrieve contact information with ease. It supports adding, deleting, searching, and listing contacts while validating email addresses and phone numbers. The application stores contacts in a JSON file for persistence.

---

### Features:
- **Add Contacts**: Input first and last names, mobile and home phone numbers, email addresses, and physical addresses.
- **Delete Contacts**: Remove contacts by name.
- **Search Contacts**: Find contacts by first or last name.
- **List Contacts**: View all stored contacts.
- **Input Validation**: Ensures valid email addresses and phone numbers are entered.
- **Persistent Storage**: Saves contacts in a JSON file to retain them between sessions.

---

### File Overview:
- `contacts.json`: Stores all contact information in JSON format.
- `main.py`: The main script that runs the application and handles user commands.

---

### How to Use:
1. Clone the repository and ensure you have Python installed.
2. Run `main.py` to start the contact manager.
3. Use the following commands to interact with the app:
   - `add`: Add a new contact.
   - `delete`: Remove a contact by name.
   - `list`: Display all saved contacts.
   - `search`: Search for a contact by first or last name.
   - `q`: Quit the application and save your contacts.

---

### Example Usage:
```bash
$ python main.py
Welcome to your contact list!

The following is a list of useable commands:
"add": Adds a contact.
"delete": Deletes a contact.
"list": Lists all contacts.
"search": Searches for a contact by name.
"q": Quits the program and saves the contact list.

Type a command: add
First Name: John
Last Name: Doe
Mobile Phone Number: 123-456-7890
Home Phone Number: 098-765-4321
Email Address: john.doe@example.com
Address: 123 Main St
Contact Added!
