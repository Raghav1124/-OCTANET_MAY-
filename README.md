# Python ATM Console Application

This Python project simulates an ATM (Automated Teller Machine) system built using console-based interface. It allows users to perform various banking operations after successfully authenticating with their user ID and PIN.

## Features

The project consists of the following classes:

1. **ATM**: Represents the ATM functionality with methods for transactions history, withdrawal, deposit, transfer, and quitting the application.

2. **User**: Represents a user of the ATM system, storing user ID and PIN.

3. **Transaction**: Represents a single transaction, storing details such as amount, type (withdrawal, deposit, transfer), and timestamp.

4. **Bank**: Represents the bank system, managing multiple users and their accounts.

5. **Main**: Contains the main program entry point where users interact with the ATM system.

## Functionality

Upon starting the application, users are prompted to enter their user ID and PIN. Once authenticated, they can perform the following operations:

- **Transactions History**: View the transaction history of their account.
- **Withdraw**: Withdraw funds from their account.
- **Deposit**: Deposit funds into their account.
- **Transfer**: Transfer funds to another user's account.
- **Quit**: Exit the application.

## Usage

To use the application, follow these steps:

1. Run the `main.py` file.
2. Enter your user ID and PIN when prompted.
3. Choose from the available options to perform transactions or view account information.

## Dependencies

This project has no external dependencies and can be run using any Python interpreter.
