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

#### Flowchart

[Inv_mgt_flowchart.pdf](https://github.com/user-attachments/files/19203034/Inv_mgt_flowchart.pdf)
[Inv_mgt_submod_flowchart.pdf](https://github.com/user-attachments/files/19203051/Inv_mgt_submod_flowchart.pdf)



