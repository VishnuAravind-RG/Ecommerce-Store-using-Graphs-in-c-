ReadMe: Delivery Management System



Overview



This project implements a Delivery Management System in C++ with features for managing orders, including take-away and home delivery services. The system simulates a warehouse with products, pricing, and an integrated delivery network.



Features



1. Product Management

• Displays a catalog of available products with prices.

• Enables customers to place orders by selecting products and quantities.



2. Take-Away Orders

• Uses an AVL Tree to manage take-away orders efficiently.

• Supports operations like:

• Insertion: Adds new orders.

• Search: Finds orders by their unique ID.

• Deletion: Removes completed orders.



3. Home Delivery Orders

• Stores delivery details, including customer name, address, and delivery charges.

• Uses Dijkstra’s Algorithm to calculate the shortest distance from the warehouse to the destination.

• Additional areas within cities are managed using Prim’s Algorithm for minimum spanning trees.



4. Order Tracking

• Displays all placed orders for home delivery.

• Lists all take-away orders sorted by order IDs.



Supported Locations



The system supports deliveries to multiple cities and areas within them, such as:

• Islamabad: I-8, Askari-14, F-10, etc.

• Lahore: Johar Town, DHA, Model Town, etc.

• Karachi: Bahria Town, North Nazimabad, Clifton, etc.

• Abbotabad: PMA, PC Hotel, Ayub Medical, etc.



Technical Highlights

• Data Structures:

• AVL Tree for take-away orders.

• Linked List for home delivery customers.

• Graph Algorithms:

• Dijkstra’s Algorithm for shortest path calculation.

• Prim’s Algorithm for minimum spanning tree.

• Modular and object-oriented design for code clarity.



How to Use

1. Compile the code using a C++ compiler (e.g., g++).

2. Run the executable to interact with the system.

3. Follow the menu-driven interface to:

• View product catalog.

• Place take-away or home delivery orders.

• Manage orders (search, display, or delete).



Future Enhancements

• Integration with a database for persistent storage.

• GUI for enhanced user experience.

• Additional features like real-time tracking and user notifications.
