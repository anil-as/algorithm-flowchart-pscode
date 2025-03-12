# Inventory management

#### Pseudocode
```
START
    DEFINE inventory as empty list
    DO
        PRINT "1. Add Item, 2. Update Item, 3. Remove Item, 4. Search Item, 5. Display Inventory, 6. Exit"
        INPUT choice
        CASE choice OF
            "1": PRINT "Enter ID, Name, Price, Quantity"
                 INPUT id, name, price, quantity
                 ADD item to inventory
            "2": PRINT "Enter ID to update"
                 INPUT id
                 FIND item
                 UPDATE quantity or price
            "3": PRINT "Enter ID to remove"
                 INPUT id
                 REMOVE item from inventory
            "4": PRINT "Enter ID or Name to search"
                 INPUT search
                 DISPLAY item if found
            "5": DISPLAY all items
            "6": PRINT "Exiting..."
                 EXIT
            DEFAULT: PRINT "Invalid Option"
        END CASE
    WHILE choice != 6
END
```
FLOWCHART
![Inv_mgt_flowchart-1](https://github.com/user-attachments/assets/cf249776-9875-4f88-a9b2-6e50e8fae57d)
![Inv_mgt_submod_flowchart-1](https://github.com/user-attachments/assets/2e3419f4-3a56-43f0-82cc-f4a6b4065792)

