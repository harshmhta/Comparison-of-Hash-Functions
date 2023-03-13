# Comparison of Hash Functions

This project consists of two hash functions, hashB and hashC, that are designed to generate hash values for a given input string. The goal is to assess the quality of these hash functions by comparing the number of collisions each function produces for a specific input file. The project uses C++ language to implement the hash functions.

## Hash Function Descriptions

### hashB Function

This function computes the hash value by initializing the hash value to zero and then iterating through each character of the input string. It then multiplies the current hash value by 16 and adds the ASCII value of the current character. Finally, the hash value is computed by taking the modulus of the result with respect to the table size of 64.

### hashC Function

This function also initializes the hash value to zero and then iterates through each character of the input string. It then multiplies the current hash value by 31 and adds the ASCII value of the current character. Finally, the hash value is computed by taking the modulus of the result with respect to the table size of 71.

## Counting Collisions
The project reads a text file called 'don.txt' that consists of 2,752 ASCII-encoded English words. The project then computes hash values for each word using both hash functions and stores them in vectors. After that, the number of collisions resulting from each hash function is calculated using the collisions function, which counts the number of duplicates in the corresponding hash value vector.

## Conclusion
The project reports the number of collisions resulting from each hash function and determines which one is the best for the tested input file. If the number of collisions resulting from the hashB function is less than that of the hashC function, then hashB is the better function. If the number of collisions resulting from hashC is less than that of the hashB function, then hashC is the better function. If both functions produce the same number of collisions, then they perform equivalently.

## Academic Integrity Statement

Please note that all work included in this project is the original work of the author, and any external sources or references have been properly cited and credited. It is strictly prohibited to copy, reproduce, or use any part of this work without proper attribution and permission from the author.

If you choose to use any part of this work as a reference or resource, you are responsible for ensuring that you do not plagiarize or violate any academic integrity policies or guidelines. The author of this work cannot be held liable for any legal or academic consequences resulting from the misuse or misappropriation of this work.

In summary, any unauthorized copying or use of this work may result in serious consequences, including but not limited to academic penalties, legal action, and damage to personal and professional reputation. Therefore, please use this work only as a reference and always ensure that you properly cite and attribute any sources or references used.
