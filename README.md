### 🍔 Ordering System (Java Console Application)

A simple **text-based ordering system** built in **Java**, inspired by fast-food menus like Jollibee and McDo 🇵🇭.  
This program allows users to **view menus, place orders, remove items, and checkout**, all through a clean console interface with proper input validation.

---

## ✨ Features

1️⃣ **Show Menu** — Displays a neatly formatted list of available meals, divided into categories (Special Meals, McDelivery Meals, and Happy Meals).  
2️⃣ **Place an Order** — Lets users select items by number, add multiple items, and view their running total.  
3️⃣ **View Current Order** — Displays all ordered items with their prices and total amount in a formatted table.  
4️⃣ **Remove Item** — Allows users to remove specific items from their order list.  
5️⃣ **Checkout** — Shows total cost, accepts payment, calculates change, and clears orders after checkout.  
6️⃣ **Input Validation** — Ensures users enter valid inputs and prevents program crashes.

---

### 🖥️ Example Output

~~~
[1] Show Menu
[2] Place an Order
[3] View Current Order
[4] Remove Item
[5] Check Out
[6] Exit

Enter your choice: 2

Placing an order...
┌------------------------------------------------------------------┐
|                            MCDO MENU                             |
└------------------------------------------------------------------┘

Special Meals:
┌------------------------------------------------------------------┐
| No.  |                     Item                        | Price   |
|------------------------------------------------------------------|
| [01] | McShare Bundle for 3 Person                     | P612.00 |
| [02] | McShare Bundle for 4 Person                     | P842.00 |
| [03] | McSpaghetti Platter - Classic Meal              | P259.00 |
| [04] | 20 Piece - Chicken McNuggets                    | P350.00 |
| [05] | Snack Burger McShare Meal - Popular             | P380.00 |
| [06] | BFF Fries N' McFloat Combo                      | P282.00 |
└------------------------------------------------------------------┘

Enter the number of your order: 1
✅ You ordered: McShare Bundle for 3 Person (₱612.00)

Want to add more? (Y/N): Y
Enter the number of your order: 10
✅ You ordered: 1-pc. Chicken McDo Happy Meal (₱185.00)

===== ORDER SUMMARY =====
┌------------------------------------------------------------------┐
| No. | Item                                         | Price       |
|------------------------------------------------------------------|
| [01] | McShare Bundle for 3 Person                 | ₱612.00     |
| [02] | 1-pc. Chicken McDo Happy Meal               | ₱185.00     |
└------------------------------------------------------------------┘

TOTAL: ₱797.00
Enter your payment: 1000
Your change: ₱203.00
✅ Thank you for ordering at McDo! Come back again!
~~~

### 🧱 Program Structure 

### Main Methods:
- **main()** – Handles the main menu loop and program logic  
- **printMenu()** – Displays menu categories and items  
- **placeAnOrder()** – Manages ordering flow and adds items  
- **viewCurrentOrder()** – Displays all current orders and totals  
- **removeAnOrder()** – Allows users to delete specific items  
- **checkoutOrder()** – Calculates total, accepts payment, and shows change  
- **validateInput()** – Ensures that only valid numbers are entered  
- **Helper Methods** – For UI borders, formatting, and menu display

---

### ⚙️ How to Run

1. **Clone or download** this repository  
2. Open a terminal or command prompt  
3. Navigate to the project directory  
4. Compile and run the Java program:
   ```java
   java OrderingSystem.java
   ```

---

### 📚 Concepts Used

- Arrays and ArrayLists  
- Methods and modular programming  
- Input handling with `Scanner`  
- Loops (`do-while`, `while`)  
- Conditional logic (`if`, `switch`)  
- String formatting using `printf()`  
- ASCII and Unicode borders for visual formatting  

---

### 👨‍💻 Author

**Michael Angelo Ricamata**  
📍 Quezon City University — BSCS Student  
📅 Created: October 2025
