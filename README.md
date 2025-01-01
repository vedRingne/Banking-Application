# Banking Application

A simple **Banking Application** built using Java. This console-based application allows users to create accounts, view account details, deposit and withdraw money, and delete accounts.

---

## Features
- **Create Account**: Open a new bank account with an initial balance.
- **View Account**: View details of an account by entering its account number.
- **Deposit Money**: Deposit a specified amount into an account.
- **Withdraw Money**: Withdraw money from an account while ensuring sufficient balance.
- **Delete Account**: Permanently delete an account from the system.
- **Error Handling**: Handles invalid inputs, duplicate accounts, and non-existent accounts.

---

## How to Use
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/banking-application.git
    cd banking-application
    ```

2. **Compile the code**:
    Ensure you have the [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) installed.
    ```bash
    javac Main.java
    ```

3. **Run the application**:
    ```bash
    java Main
    ```

4. **Follow the on-screen menu**:
    - Enter the corresponding number to perform actions:
        1. Create Account
        2. View Account
        3. Deposit
        4. Withdraw
        5. Delete Account
        6. Exit the application

---

## Code Overview
- **`BankAccount` Class**:
  - Represents a bank account with attributes: account number, account holder name, and balance.
  - Provides methods to deposit, withdraw, and view account details.
  - Validates deposit and withdrawal amounts.

- **`Main` Class**:
  - Implements the main logic of the application.
  - Provides a menu-driven interface to interact with the banking system.
  - Stores accounts in a `HashMap` for efficient retrieval and management.

---

## Example Usage
```plaintext
Banking Application
1. Create Account
2. View Account
3. Deposit
4. Withdraw
5. Delete Account
6. Exit
Enter your choice: 1

Enter Account Number: 12345
Enter Account Holder Name: John Doe
Enter Initial Balance: 500
Account created successfully!

Banking Application
Enter your choice: 2

Enter Account Number: 12345
Account Number: 12345, Account Holder: John Doe, Balance: 500.0
