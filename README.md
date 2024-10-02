# Binary Tree vs. Red-Black Tree: AI-Assisted Performance Comparison Kata

## Overview

This kata is designed to give developers hands-on experience with two fundamental data structures—Binary Search Trees (BST) and Red-Black Trees (RBT)—while encouraging the use of AI tools as an augmentation to their coding skills.

Participants will implement both a binary search tree and a red-black tree, instrumented to count the number of operations (insertions, deletions, and lookups). By comparing the performance of these trees on two datasets (one sorted and one randomized), participants will gain insights into the efficiency of these structures under different conditions.

### AI Integration
- **Copilot**: You can rely on Copilot to assist with code generation, such as building the tree structures and counting operations. However, it's important to review, modify, and understand the code that is generated. NOTE: If you don't have access to Copilot, you can use ChatGPT or any other AI client to generate the code.
- **ChatGPT**: ChatGPT is available for answering questions, providing clarifications, or offering explanations about tree structures, algorithm efficiency, or the performance analysis.

---

## Kata Requirements

### 1. Data Structures
- **Binary Search Tree**: A traditional binary search tree (BST) with insertion, deletion, and search methods.
- **Red-Black Tree**: A self-balancing binary tree that maintains balance via color-coding nodes. This tree should implement balancing logic for insertions and deletions.

### 2. Instrumentation
- Each operation (insertions, deletions, and lookups) should be instrumented to count the number of steps or comparisons made during execution.

### 3. Datasets
- **Sorted List**: One file contains a list of over 100,000 names sorted alphabetically.
- **Randomized List**: Another file contains the same names, but in a random order.
- Both files will be used for insertion, deletion, and lookup operations, with performance comparisons made between the datasets.

### 4. Operations to Implement
- **Insertion**: Insert all names from both datasets into the binary search tree and the red-black tree.
- **Lookup**: Perform lookups on a random subset of names in both trees and record the number of comparisons.
- **Deletion**: Remove a random subset of names from both trees and track the number of operations.

### 5. Comparative Analysis
- Compare the number of operations for insertions, lookups, and deletions between the two tree structures for both datasets (sorted and random).
  
---

## Step-by-Step Instructions

### Step 1: Project Setup
- **Responsibility**: Programmer
   - Create a folder to contain the project
   - Clone this repository
   - Create a branch to contain your code
   - Choose an implementation language
   - The repository contains two input data files:
     - `sorted_names.txt`: Contains a list of over 100,000 names sorted alphabetically.
     - `randomized_names.txt`: Contains the same list but in random order.

### Step 2: Define the Binary Search Tree Class
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Use Copilot to generate a BST class, including methods for insertion, deletion, and search. You will probably also want a method to print out the tree so you can verify the operation of the code.
   - **Copilot**: Assist with generating the BST class and it's requisite methods.
 
### Step 3: Write tests verify the the tree and it's method are correct.
- **Responsibility**: Programmer and Copilot
  - **Programmer**: Use Copilot to generate tests to verify insertion, deletion, search, and print for the BST.
  - **Copilot**: Generate the tests.

### Step 4: Instrument the Binary Search Tree
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Use Copilot to insert counters to track the number of comparisons performed by each method for each method. Ensure you are able to roll up the counters to a total number of comparisons and that you are able to retrieve the counts.
   - **Copilot**: Help suggest where to place counters and assist with incrementing/rollup logic.
 
### Step 5: Write tests verify the the instrumentation is working correctly.
- **Responsibility**: Programmer and Copilot
  - **Programmer**: Use Copilot to generate tests to verify instrumentation.
  - **Copilot**: Generate the tests.
  - 
### Step 6: Define the Red-Black Tree Class
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Use Copilot to generate a red-black tree, including insertion, deletion, rebalance, and search with balancing logic.
   - **Copilot**: Assist with generating the RBT and its methods.
 
### Step 7: Write tests verify the the RBT and it's method are correct.
- **Responsibility**: Programmer and Copilot
  - **Programmer**: Use Copilot to generate tests to verify all methods for the BST. Include tests to verify that the RBT is remaining balanced.
  - **Copilot**: Generate the tests.

### Step 8: Instrument the Red-Black Tree
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Instrument the red-black tree to count operations.
   - **Copilot**: Assist with logic to track and count operations within the balancing methods.
 
### Step 9: Write tests verify the the instrumentation for the RBT is working correctly.
- **Responsibility**: Programmer and Copilot
  - **Programmer**: Use Copilot to generate tests to verify instrumentation.
  - **Copilot**: Generate the tests.

### Step 10: For each of the full datasets and each type of tree, write tests to measure performance.:
#### Step 10a: Load the dataset into the tree and record the number of operations.
#### Step 10b: Insert a number of test strings at different places in the alphabet and record the number of operations.
#### Step 10c: Delete the strings inserted in the previous step and record the number of operations.
#### Note: You should have 4 executions for Steps 10a-10c,  
- **Responsibility**: Programmer & Copilot
   - **Programmer**:Use Copilot to generate the tests. Verify tha the code is correct.
   - **Copilot**: Help generate the tests.

### Step 11: Compare the performance of each of the trees
- **Responsibility**: Programmer
   - Record the number of operations generated in Step 10 in a table for easy comparison.


---

## Evaluation Criteria
- Proper implementation of both binary search tree and red-black tree.
- Accurate instrumentation for counting operations.
- Clear comparison of results for both datasets.
- Effective use of Copilot and ChatGPT to assist, without relying solely on AI to complete the task.

---

Happy coding! Use AI to assist, but remember—**you** are the one in control of your code.

