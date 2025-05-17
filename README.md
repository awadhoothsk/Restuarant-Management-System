# Restaurant Management System 🍽️

A terminal-based Restaurant Management System built using **C**. It features separate workflows for **admin** and **customer** roles and leverages **doubly linked lists** for managing menu items, orders, and sales data.

---

## 🛠 Features

### 👨‍🍳 Admin Section
- View total sales
- Add new items to the order menu
- Delete items from the order menu
- Display the current menu

### 👤 Customer Section
- Place an order
- View ordered items
- Delete items from your order
- Display final bill with total amount

---

## 🧾 Technologies Used

- **Language**: C
- **Data Structure**: Doubly Linked List
- **IDE**: Visual Studio Code (VS Code)
- **Compiler**: GCC (via MinGW or WSL)

---

## 🚀 Getting Started in VS Code (Windows)

### ✅ Step 1: Install Prerequisites

- Install [VS Code](https://code.visualstudio.com/)
- Install [MinGW](https://www.mingw-w64.org/downloads/) and add `bin` path to **System Environment Variables**
- Install C/C++ Extension in VS Code (Microsoft)
- Restart your system if needed

### ✅ Step 2: VS Code Configuration (Optional)

1. In VS Code, go to settings and search for `code-runner.executorMap`
2. Add this under your workspace or global `settings.json`:

```json
{
  "code-runner.executorMap": {
    "c": "gcc \"$file\" -o \"$fileNameWithoutExt\" && \"$fileNameWithoutExt\""
  },
  "code-runner.runInTerminal": true
}
# Compile the code
gcc ds.c -o restaurant.exe

# Run the program
./restaurant.exe
