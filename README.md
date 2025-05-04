# ComputationalTheory

This repository was created for the Computational Theory module. It contains the tasks and solutions completed throughout the semester.


## Contents
- 'taks.jpynb' - Main notebook with all tasks and explanations
- 'test.txt' - Used for SHA-256 padding test
- 'words.txt' - Massive file, contrains sample data for task 6

## Tasks Overview

### Task 1: Binary Representations
- Working with binary numbers
- Converts between binary and decimal
- Used examples to demonstrate bitwise operations
### Task 2: Hash Functions
- Converted a basic C-style hash function into Python
- Used **ord()** and modular arithmetifcs to create hash values
- Tested on strings to see different outputs
### Task 3: SHA256
- Implemented the padding used in SHA-256
- Converted input to binary, added padding and appended length
- Used **test.txt** to verify correct formatting
### Task 4: Prime Numbers
- Generated the first 100 prime numbers
- Used two methods: Trial Division and Sieve of Eratosthenes
- Compared both for accuracy and performance
### Task 5: Roots
- Calculated square roots of prime numbers
- Exctracted only the decimla part and converted to 32-bit int
- Used this method to simulate how constrants are generated for cryptographic algorithms like SHA-256
### Task 6: Proof of Work
- Simple proof-of-word system
- Searched for a value that makes the hash of input data start with a certrain number of zeros
- Used concept of a blockchain mining to verify blocks
### Task 7: Turing Machines
- Sumulates a Turing machine in Python
- Used a state table and an input string to process the tape
- Shows how basic Turing machine read, write, and change states
### Task 8: Computational Complexity
- Measured how many coomparisions bubble sort makes for different input orders
- Generated all permutations of a list and counted sorting steps
- Helped understand algorithm efficienct by tracking comparision counts
