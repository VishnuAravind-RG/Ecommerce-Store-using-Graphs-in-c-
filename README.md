# Delivery Management System

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Overview
This project implements a **Delivery Management System** in **C++**, providing an efficient way to manage orders, including **take-away** and **home delivery** services. The system simulates a **warehouse** with products, pricing, and an integrated delivery network.

## 📁 Project Structure
```
📂 Delivery-Management-System
├── 📄 CMakeLists.txt    # Build configuration
├── 📂 src              # Source code
│   ├── main.cpp       # Core implementation
│   ├── order.cpp      # Order management logic
│   ├── order.h        # Header file
├── 📂 examples         # Sample input/output
├── 📄 README.md        # Project documentation
├── 📄 LICENSE          # MIT License details
```

## ⚙️ Installation & Compilation
### Prerequisites
- C++ Compiler (GCC, Clang, or MSVC)
- CMake (for cross-platform building)

### Steps to Compile & Run
```bash
# Clone the repository
git clone https://github.com/yourusername/Delivery-Management-System.git
cd Delivery-Management-System

# Build using CMake
mkdir build && cd build
cmake ..
make

# Run the executable
./delivery_system
```

## 🎯 Features
### 1️⃣ **Product Management**
✅ Displays a catalog of available products with prices  
✅ Enables customers to place orders by selecting products and quantities  

### 2️⃣ **Take-Away Orders**
✅ Uses an **AVL Tree** for efficient order management  
✅ Supports operations such as:
   - **Insertion**: Adds new orders  
   - **Search**: Retrieves existing orders  
   - **Deletion**: Cancels completed orders  

### 3️⃣ **Home Delivery Orders**
✅ Uses a **Priority Queue** to prioritize urgent deliveries  
✅ Assigns delivery personnel based on availability  
✅ Optimized scheduling for faster deliveries  

### 4️⃣ **Order Tracking**
✅ Displays the real-time status of orders  
✅ Allows customers to check expected delivery times  
✅ Updates dynamically based on order progress  

## 📌 Sample Input
```plaintext
Available Products:
1. Pizza - $10
2. Burger - $5
3. Pasta - $8

Enter order type (1: Take-Away, 2: Home Delivery): 1
Enter product ID and quantity: 2 3
Order placed successfully!
```

## 📌 Sample Output
```plaintext
[LOG] Current Orders:
Take-Away Orders (AVL Tree):
- Order ID: 101 | Product: Burger | Quantity: 3

Home Delivery Orders (Priority Queue):
- Order ID: 202 | Product: Pizza | Quantity: 1 | Status: Dispatched
```

## 🔍 How It Works
1. **Order Placement**: Customers select products and order type.
2. **Data Structure Utilization**:
   - **AVL Tree**: Balances take-away orders.
   - **Priority Queue**: Manages delivery scheduling.
3. **Order Processing**: Orders are fulfilled based on availability and priority.
4. **Real-Time Updates**: Order status updates dynamically.

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 📢 Contributing
1. Fork the repository 🍴
2. Create a new branch 🚀 (`git checkout -b feature-name`)
3. Commit changes 🎯 (`git commit -m 'Add feature'`)
4. Push to branch ⬆️ (`git push origin feature-name`)
5. Submit a Pull Request 🤝



---
💡 _"Efficient order management ensures seamless deliveries!"_ 🚀

