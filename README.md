# ATM Simulation System  

## Overview  
This project is a simple console-based ATM simulation written in Java. It allows users to log in with a PIN, check their account balance, withdraw money, deposit funds, and exit the application. The program is designed to demonstrate basic programming concepts and user interactions in Java.  

---

## Features  
- **User Authentication**: Secure PIN-based login system.  
- **Check Balance**: Displays the user's current balance.  
- **Withdraw Cash**: Allows users to withdraw money while ensuring sufficient funds.  
- **Deposit Cash**: Lets users deposit money into their account.  
- **Exit**: Ends the session safely.  

---

## Technologies Used  
- **Programming Language**: Java  
- **Development Environment**:  
  - Java Development Kit (JDK)  
  - Any text editor or IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)  

---

## Flow of Execution  

### 1. Start the Application  
- The program begins with a welcome message and prompts the user to enter their PIN.  

### 2. PIN Authentication  
- The user must enter the correct PIN (default: 1234).  
- If the PIN is incorrect, access is denied, and the program exits.  

### 3. Main Menu Options  
After successful authentication, the following menu is displayed:  
1. **Check Balance**:  
   - Displays the current account balance.  
2. **Withdraw Cash**:  
   - Prompts the user for a withdrawal amount.  
   - Ensures the amount is valid and does not exceed the balance.  
3. **Deposit Cash**:  
   - Prompts the user for a deposit amount.  
   - Adds the amount to the balance if valid.  
4. **Exit**:  
   - Ends the session and displays a goodbye message.  

### 4. Transaction Handling  
- The menu is displayed after each transaction until the user selects "Exit."  

---

## Screenshots  

### Welcome Screen  
```plaintext
Welcome to the ATM!
Enter your PIN: _
