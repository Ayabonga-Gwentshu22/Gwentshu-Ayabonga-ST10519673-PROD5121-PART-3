##  Project Overview
QuickChat is a Java-based messaging system that allows users to:
- Register and log in securely
- Send, store, or disregard messages
- Generate message IDs and hashes
- Store messages using parallel arrays
- Search, delete, and display message reports

The system demonstrates the use of:
- Object-Oriented Programming (OOP)
- Parallel arrays
- Input validation
- File handling
- Menu-driven console application

---

##  Project Structure

The system contains the following classes:

- `MainApp` → Main menu and program entry point
- `MessageTest` → Handles registration, login, and message creation
- `LoginForm` → Validates user credentials
- `Message` → Handles message creation, validation, and storage
- `MessageManager` → Stores messages using parallel arrays
- `MessageProcessor` → Handles searching, reporting, and deletion

---

##  Features

### 1. User Registration
- Validates username (must contain underscore and max 5 characters)
- Validates password (8+ characters, uppercase, number, special character)
- Validates South African phone numbers (+27 format)

---

### 2. Login System
- Users must log in using registered credentials
- Displays success or failure messages

---

### 3. Message Handling
Users can:
- Send messages
- Store messages
