# Java Bank Account Program

This repository contains a simple Java program that demonstrates **Object-Oriented Programming (OOP)** concepts using a `BankAccount` class.

## Features
- Create a bank account with an account holder and balance.
- Deposit money into the account.
- Display account details and balance.

## Code Example
```java
class BankAccount {
    String AccountHolder;
    int balance;

    void deposit(int amount) {
        balance += amount;
    }

    void displayBalance() {
        System.out.println("Account Holder = " + AccountHolder);
        System.out.println("Balance = " + balance);
    }
}

public class Main {
    public static void main(String[] args) {
        BankAccount b1 = new BankAccount();
        b1.AccountHolder = "James";
        b1.balance = 10000;

        b1.deposit(5000);
        b1.displayBalance();
    }
}
bash
git clone https://github.com/Sksanjay12/java-bank-account.git
