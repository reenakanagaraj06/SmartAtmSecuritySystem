# Smart ATM Security System

A beginner-friendly Java console application that simulates basic ATM security and withdrawal validation.

## 📌 Project Overview

The Smart ATM Security System checks whether a user is allowed to access an ATM and withdraw money.

The system verifies:

* Whether the card is valid
* Whether the PIN is correct
* Whether the account is active
* Whether the user is blocked
* Whether the withdrawal amount is valid
* Whether sufficient balance is available

If all required conditions are satisfied, the system allows the withdrawal and calculates the remaining balance.

## 🛠️ Technologies Used

* Java
* Java Scanner
* Boolean and logical operators
* Conditional statements
* Arithmetic operations

## ⚙️ How It Works

The user provides:

1. Card validity
2. PIN correctness
3. Account status
4. User blocked status
5. Account balance
6. Withdrawal amount

The program first checks ATM access:

```java
cardValid && pinCorrect && accountActive && !userBlocked
```

Then it checks whether the withdrawal is allowed:

```java
withdrawAmount > 0 && withdrawAmount <= balance && atm_access
```

If the withdrawal is successful, the remaining balance is calculated.

## ▶️ Example Input

```text
true
true
true
false
50000
1000
```

## 📤 Example Output

```text
remaining balance : 49000.0
ATM access: true
Withdrawel allowed: true
```

## 📚 Concepts Practiced

* Variables
* Data types
* `Scanner`
* Boolean values
* Logical operators
* Relational operators
* `if` statements
* Arithmetic operations
* User input
* Basic Java program structure

## 🎯 Purpose

This project was created as a beginner Java practice project to understand conditional logic, boolean expressions, user input, and basic Git/GitHub workflow.

## 👩‍💻 Author

**Reena Kanagaraj**

GitHub: `reenakanagar06`
