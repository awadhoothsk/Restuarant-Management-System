# Restaurant Management System 🍽️

This is a command-line-based Restaurant Management System written in **C**. It supports basic functionalities for **admin** and **customer** roles. The project uses **doubly linked lists** to manage menu items, orders, and sales data efficiently.

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
- Delete items from the order
- Display final bill with total amount

---

## 🧾 Data Structures Used
- **Doubly Linked List**: Used to manage the menu, customer orders, and total sales.
- **Structs**: Defined for each node to hold food item details.

---

## 🚀 Getting Started

### ✅ Prerequisites
- GCC compiler (or Code::Blocks with GCC setup)
- Git (optional, for cloning/pushing to GitHub)

### 💻 Running the Code

#### Method 1: Using Code::Blocks
1. Open Code::Blocks.
2. Open the `.cbp` project or create a new one and add `ds.c`.
3. Click **Build and Run** (`F9`).

#### Method 2: Using Terminal (VS Code or Git Bash)

```bash
# Navigate to your project folder
cd /d/restarunt

# Compile the code
gcc ds.c -o restaurant

# Run the compiled program
./restaurant

