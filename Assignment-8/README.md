# Data Structures and Algorithms (CS506)
# Lab Assignment 8  

1. In this lab assignment you need to write a C-program to construct Huffman codes. To be precise, your program should first ask the user to press **1** or **2**.

    **Case 1**: That is, the user has pressed a **1**: In this case, your program should ask the user to enter a “**character-frequency**” table. See the test cases below for the details.
Construct the Huffman code for the character-frequency table, and print the Huffman-code table for the same. See test cases for the same. Your program should stop here in this case.
    
    **Case 2**: That is, the user has pressed a **2**: In this case, your program should
    read the file “**data.txt**” and construct the “**character-frequency table**”: constructing the character-frequency table is simple. Just read the file “**data.txt**”
    one character at a time. If the character is not present in the table, add it ith a frequency of **1**. If the character is already present in the table, just
    increment its frequency. Your program should print the character-frequency table on a separate file **FrequencyData.txt**.
    
    Now, construct the Huffman code for the character-frequency table, and print the Huffman-code table on a separate file **HuffmanCodeData.txt**.
    
    Now, your program should use the Huffman code to encode the file “**data.txt**”: repeatedly read the next character in the file **data.txt**, look up the Huffman code for the character in the Huffman-code table, and then write the sequence of **0**s and **1**s in that codeword as bits to an output file “**EncodedData.txt**”. At this moment your program has encoded the file **data.txt** into the file **EncodedData.txt** using the Huffman coding. 
    
    Your program should now decode the file **EncodedData.txt** into the output file “**DecodedData.txt**”.
    Decode the file **EncodedData.txt**: For decoding the file simply identify the initial codeword, translate it back to the original character, write the character to an output file **DecodedData.txt**, and repeat the decoding process on the remainder of the **EncodeData.txt** file. Pick the initial codeword using the binary tree corresponding to the Huffman code. 

   Refer the Section 16.3 of the book CLRS for the details of Huffman coding.

    Test Case :
    
        Enter 1 or 2:
        You entered a 1:
        Enter character-frequency table:
        a 45
        b 13
        c 12
        d 16
        e 9
        f 5
        Huffman code table is as follows:
        Char codeword
        a 0
        b 101
        c 100
        d 111
        e 1101
        f 1100
        
 Sol. Download the [Solution](solution.o) file. Open terminal and execute it by running `./solution.o` command. [data.txt](data.txt) file is present.

    ![Output1a](output/Solution1a.png)
    ![Output1b](output/Solution1b.png)
