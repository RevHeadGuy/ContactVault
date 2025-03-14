**ContactVault** 📞🔐

A simple and efficient Phonebook Management System built using C++.

📌 Overview

ContactVault is a command-line-based phonebook management system that allows users to store, search, modify, and delete contacts seamlessly. It uses a doubly linked list for efficient contact handling and file storage to persist data across sessions. The interface is enhanced with ANSI escape codes for a visually appealing experience.

🚀 Features

📌 Add Contacts – Store names, phone numbers, and email addresses.

🔎 Search Contacts – Find contacts instantly by name or phone number.

✏️ Modify Contacts – Update contact details while maintaining data integrity.

🗑️ Delete Contacts – Remove contacts safely without memory leaks.

💾 Data Persistence – Automatically saves contacts to a file (contacts.txt) and loads them on startup.

🎨 Enhanced UI – Uses ANSI escape codes for a better user experience in the terminal.

🛠️ Tech Stack

Programming Language: C++

Data Structures: Doubly Linked List

File Handling: .txt file for persistent storage

Terminal Styling: ANSI escape codes

🔧 How to Use

Compile the Code:

g++ contactvault.cpp -o contactvault

Run the Program:

./contactvault

Choose an Option from the Menu:

1️⃣ Add a new contact

2️⃣ Display all contacts

3️⃣ Search for a contact

4️⃣ Modify a contact

5️⃣ Delete a contact

6️⃣ Save and exit

📂 File Storage
Contacts are saved in contacts.txt to ensure data is not lost after closing the program.
On startup, the program loads saved contacts automatically.

📜 License

This project is open-source and free to use for learning and development purposes.
