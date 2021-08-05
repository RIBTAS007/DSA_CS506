# Data Structures and Algorithms (CS506)
# Lab Assignment 6 

1.  You need to implement a hash table where collisions are resolved via chaining with doubly linked lists. Your program should first ask the user for the hash table size **m**. Use **h(k) = k mod m** as the hash function. Your program should support the insert, delete, search and display operations.

    For insertion, your program should ask user to enter a data **k** to insert, find the slot **h(k)** and insert the key **k** into the head of the doubly linked list corresponding to the slot **h(k)**. The delete operation should first ask user to enter a data **k** you want to delete. Then the delete operation delete **k** from the doubly linked list corresponding to the slot **h(k)**, if **k** is present. Othewise,do nothing.

    Search operation ask user to enter a data k to search, and then search **k**. If **k** is not present, print: not present, else print present in slot number **h(k)**. Display operation displays the entire data stored in the hash table. Print the data nicely: a newline for each doubly linked lists (corresponding to each slot). Refer some test cases below:

    **Test cases**:
   
    **Enter hash table size m**: 10

    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit

    **Enter your choice**: 1<br>
    **Enter value to insert**: 10<br>

    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit

    **Enter your choice**: 1<br>
    **Enter value to insert**: 120<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 1<br>
    **Enter value to insert**: 19<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 1<br>
    **Enter value to insert**: 5<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 1<br>
    **Enter value to insert**: 20<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 1<br>
    **Enter value to insert**: 30<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 1<br>
    **Enter value to insert**: 40<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 4<br>
    
    index 0: 40 30 20 120 10<br>
    index 1: NULL<br>
    index 2: NULL<br>
    index 3: NULL<br>
    index 4: NULL<br>
    index 5: 5<br>
    index 6: NULL<br>
    index 7: NULL<br>
    index 8: NULL<br>
    index 9: 19<br>
    
    1. Insert
    2. Delete
    3. Search
    4. Display
    5. Quit
    
    **Enter your choice**: 5<br>
    
Sol. Download the [Solution](solution.o) file. Open terminal and execute it by running `./solution.o` command. Give inputs to get outputs

   ![Output](output/solution.png)
