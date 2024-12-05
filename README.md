# Bankist App [Live](https://bppatkar.github.io/Bhanu_Bank_javascript)

The **Bankist App** is a mock banking application designed to demonstrate key banking functionalities with an interactive and dynamic user interface. It is built using JavaScript, HTML, and CSS, showcasing modern techniques like date formatting, internationalization, and real-time updates.

---

## Test Accounts

### User 1
- **Username**: `bpp`
- **PIN**: `1111`

### User 2
- **Username**: `ap`
- **PIN**: `2222`

## Features

### 1. User Login
- Secure login using username and PIN.
- Personalized welcome message displayed upon login.
- Shows the current date and time in the user's locale.

### 2. Transaction Management
- Displays all transactions (deposits and withdrawals) with formatted dates.
- Allows sorting of transactions in ascending or descending order.

### 3. Money Transfer
- Transfer funds to another account by entering the recipient's username and transfer amount.
- Updates the balances and transaction history for both accounts in real-time.

### 4. Loan Requests
- Users can request loans, which are granted if the requested amount is at least 10% of an existing deposit.
- Loan approval is delayed by 2.5 seconds to simulate processing time.

### 5. Account Closure
- Accounts can be closed by providing the username and PIN.
- Removes the account from the app and clears the UI.

### 6. Auto Logout Timer
- Implements a 2-minute countdown timer to automatically log users out after inactivity.

### 7. Localization
- Supports date and currency formatting based on the user's locale and account currency.
- Relative date descriptions like "Today," "Yesterday," or "3 days ago" for recent transactions.

---

## Technology Stack

- **HTML**: Provides the structural layout of the application.
- **CSS**: Ensures a visually appealing and responsive design.
- **JavaScript**: Powers the app's dynamic features, validations, and interactions.

