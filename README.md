# Premier ATM System 🏦

A fully functional, console-based ATM simulation program written in x86 Assembly language. This project was developed for the Computer Organization and Architecture course (Degree Year 1, Semester 3) as part of the Bachelor of Software Engineering (Honours) program at Tunku Abdul Rahman University of Management and Technology (TARUMT).

## 🚀 Overview

The Premier ATM System simulates a real-world banking interface, providing users with a secure and interactive environment to manage their finances. It features a robust text-based UI with color-coded feedback, masked secure inputs, and a variety of banking and financial calculation tools.

## ✨ Features

* **Secure Authentication:** Requires an 8-digit credit card number and a PIN. The PIN input is securely masked with asterisks (`*`).
* **Core Banking Operations:**
  * **Deposit & Withdraw:** Handles transactions with precise RM and Sen formatting, preventing overdrafts and calculating exact bill breakdowns (RM100, RM50, RM20, etc.) for withdrawals.
  * **Check Balance:** Real-time balance updates displayed in full RM/Sen format.
* **Currency Conversion:** Allows users to convert and withdraw funds in foreign currencies (USD, EUR, GBP, JPY, AUD) based on predefined exchange rates.
* **Future Value Calculator:** Computes compound interest over a specified number of years based on regular yearly deposits and annual interest rates.
* **Rewards System:**
  * Earn points based on deposit amounts.
  * Redeem points for direct cash credited back to the account.
  * Redeem points for promotional discount vouchers.
  * Estimate future reward points based on projected monthly deposits.
* **Dynamic UI & Receipts:** Implements dynamic text coloring for error handling (red), success messages (green), and financial values (yellow). Generates detailed transaction receipts complete with the current system date and time.

## 🛠️ Tech Stack

* **Language:** x86 Assembly Language (MASM)
* **Library:** `Irvine32.inc` (Kip Irvine's standard library for x86 assembly)
* **Environment:** Microsoft Visual Studio 2022

## 🔑 Login Credentials

To access the system, use the following test credentials:

**Credit Card Options (8-digits):**
* Account 1: `11112222`
* Account 2: `33334444`

**PIN Number:** * `718111`

## ⚙️ How to Run

1. Clone this repository to your local machine.
2. Ensure you have **Microsoft Visual Studio 2022** installed with the **Desktop development with C++** workload.
3. You must have the **Irvine32 library** installed and configured in your Visual Studio environment. 
4. Open the `Banking Program.sln` file in Visual Studio.
5. Build and run the project (Local Windows Debugger) to launch the ATM console.

## 👨‍💻 Development Team

* **Ting Rong You**
* **Yong Chong Xin**
* **Wan Zi Kang**
* **Sik Zhe Yang**

---
*Developed as an academic assignment for the Computer Organization and Architecture course.*
