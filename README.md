# 🛒 Inventory and Transaction Management System

The **Inventory and Transaction Management System** is a Go-based program for managing item data, incoming transactions, and outgoing transactions. This program supports various features, such as adding, updating, and deleting item and transaction data, as well as searching for data based on keywords or categories.

---

## ✨ Key Features

### 1. **Item and Transaction Management**
- Add new items and record incoming/outgoing transaction times.
- Update item and transaction data through an interactive menu.
- Delete specific item and transaction data.

### 2. **Item Data Search**
- Search for items by:
  - Name
  - Type
  - Stock quantity (using binary search, sequential search, selection sort, or insertion sort)
  - Category

### 3. **Preset Data**
- Provides initial preset data for quick simulations and testing.

### 4. **Display All Data**
- Displays all item data along with the transaction times in a structured format.

---

## 🛠️ Technologies Used
- **Programming Language**: Go (Golang)
- **Data Structures**: Static arrays for storing items and transactions.
- **Sorting & Searching Algorithms**:
  - Binary Search
  - Sequential Search
  - Selection Sort (Ascending)
  - Insertion Sort (Descending)

---

## 📄 Program Structure

### **Data Types**
- **`barang`**: Structure for storing item information (name, type, stock, category).
- **`Transaksi`**: Structure for storing transaction times (hour, minute, second).
- Arrays: `tabBarang`, `tabMasuk`, `tabKeluar` are used to store item and transaction data.

### **Main Functions**
- **`main()`**: The main menu to choose program features.
- **`presetData()`**: Provides initial data for quick simulations.
- **`PencatatanBarangdanTransaksi()`**: Menu for adding, updating, or deleting item and transaction data.
- **`pencariankatakuncibarang()`**: Searches for item data by keywords.
- **`pencarianStok()`**: Searches for stock quantities using various algorithms.

---

## 🚀 How to Use

1. **Run the program** in an environment that supports Go.
2. **Choose a menu** from the available options:
   - **Item and Transaction Data**: Manage item and transaction data.
   - **Keyword Search**: Search for items by name or type.
   - **Category Search**: Search for items by a specific category.
   - **Display All Data**: Show all item and transaction data.
3. **Follow the instructions** to add, update, or delete data.

---

## 📌 Example Preset Data

The program starts with the following sample data:
- **Items**: Fish, Chicken, Bird with various categories such as "Water," "Land," and "Air."
- **Transaction Times**: Predefined incoming and outgoing transaction times.

---
