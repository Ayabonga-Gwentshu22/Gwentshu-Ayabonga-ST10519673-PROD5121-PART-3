##  Project Overview
QuickChat is a Java-based messaging system that allows users to:
- Register and log in securely
- Send, store, or disregard messages
- Generate message IDs and hashes
- Store messages using parallel arrays
- Search, delete, and display message reports.


---

##  Project Structure

The system contains the following classes:

- MainApp this handles main menu and program entry point
- MessageTestHandles this handles registration, login, and message creation
- LoginForm this validates user credentials
- Message this Handles message creation, validation, and storage
- MessageManager this stores messages using parallel arrays
- MessageProcessor this handles searching, reporting, and deletion

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

  
### 4. Message Storage (Parallel Arrays)
Messages are stored using:
- recipients[]
- senders[]
- messageHashes[]
- messageIds[]
- flags[]
- sentMessages[]
- storedMessages[]
- disregardedMessages[]

---

### 5. Search Functionality
The system can:
- Search messages by recipient
- Search messages by message ID

---

### 6. Reporting
- Display all stored messages
- Show developer and recipient pairs
- Display full message report

---

### 7. Delete Feature
- Messages can be deleted using their hash
- Arrays are shifted correctly after deletion

---

### 8. Longest Message Feature
- Finds and displays the longest stored message
