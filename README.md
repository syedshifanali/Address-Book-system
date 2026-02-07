# Address Book Management System (C)

## Overview
The Address Book Management System is a console-based application developed in the C programming language. It allows users to store, manage, and retrieve contact information efficiently. The system simulates a real-world contact management application using fundamental programming concepts.

This project focuses on structured programming, file handling, and memory management, making it suitable for beginner to intermediate system and embedded software roles.

## Features
- Add new contacts
- View all saved contacts
- Search contacts by name or phone number
- Edit existing contact details
- Delete contacts
- Data persistence using file handling

## Technologies Used
- Language: C
- Concepts:
  - Structures
  - Pointers
  - File handling
  - Dynamic memory allocation
  - Functions and modular programming
  - 
## Project Flow
1. Program starts and loads existing contact data from file into memory.
2. A menu is displayed to the user with available operations.
3. User selects an option from the menu:
   - Add Contact
   - View Contacts
   - Search Contact
   - Edit Contact
   - Delete Contact
4. Based on the selected option:
   - Input is taken from the user.
   - Required operation is performed using structures and functions.
5. Updated contact information is written back to the file.
6. User is asked whether to continue or exit.
7. Program terminates safely after saving all data.

## Usage

### Compilation
gcc *.c -o addressbook

### Execution
./addressbook

## Project Structure
Address-Book-System/
│
├── add_contact.c
├── view_contact.c
├── search_contact.c
├── edit_contact.c
├── delete_contact.c
├── file_operations.c
├── types.h
├── main.c
└── README.md

## Limitations
- Console-based interface only
- Limited input validation
- No encryption for stored data

## Future Enhancements
- Add password protection
- Implement sorting of contacts
- Improve input validation
- Add GUI support

## Learning Outcomes
- Strong understanding of structures and pointers
- Practical experience with file handling
- Improved logical thinking and problem-solving skills
- Exposure to real-world data management applications

## Author
Syed Shifan Ali
