# Binary Tree vs. Red-Black Tree: AI-Assisted Performance Comparison Kata

## Overview

This kata is designed to give developers hands-on experience with two fundamental data structures—Binary Search Trees (BST) and Red-Black Trees (RBT)—while encouraging the use of AI tools as an augmentation to their coding skills.

Participants will implement both a binary search tree and a red-black tree, instrumented to count the number of operations (insertions, deletions, and lookups). By comparing the performance of these trees on two datasets (one sorted and one randomized), participants will gain insights into the efficiency of these structures under different conditions.

### AI Integration
- **Copilot**: You can rely on Copilot to assist with code generation, such as building the tree structures and counting operations. However, it's important to review, modify, and understand the code that is generated.
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
   - **Programmer**: Outline the class structure for the binary tree, including methods for insertion, deletion, and search.
   - **Copilot**: Assist with generating the basic structure for the BST.

### Step 3: Instrument the Binary Search Tree
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Insert counters to track the number of operations (comparisons/steps) for each method.
   - **Copilot**: Help suggest where to place counters and assist with incrementing logic.

### Step 4: Consult ChatGPT for Tree Performance Insights
- **Responsibility**: Programmer & ChatGPT
   - **Programmer**: If uncertain about how to count operations or the degenerate nature of binary trees, ask ChatGPT.
   - **ChatGPT**: Provide explanations on binary tree behavior when unbalanced.

### Step 5: Define the Red-Black Tree Class
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Outline the class structure for the red-black tree, including insertion, deletion, and search with balancing logic.
   - **Copilot**: Assist with generating the scaffolding for the RBT and its balancing methods.

### Step 6: Instrument the Red-Black Tree
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Instrument the red-black tree to count operations.
   - **Copilot**: Assist with logic to track and count operations within the balancing methods.

### Step 7: Verify the Balancing Logic
- **Responsibility**: Programmer & ChatGPT
   - **Programmer**: If unsure about red-black tree balancing rules, consult ChatGPT.
   - **ChatGPT**: Provide explanations of red-black tree properties (e.g., red/black rules, balancing).

### Step 8: Load the Datasets into the Trees
- **Responsibility**: Programmer & Copilot
   - **Programmer**: Write code to read the sorted and randomized datasets.
   - **Copilot**: Help generate code to load the data into the tree structures.

### Step 9: Perform Batch Insertions
- **Responsibility**: Programmer
   - Insert all names from the datasets into both tree structures and count the number of operations.

### Step 10: Perform Batch Lookups
- **Responsibility**: Programmer and ChatGPT
   - **Programmer**: Select a random subset of names and perform lookups in both trees. Count the number of comparisons.
   - **ChatGPT**: Assist in extracting a randome subset of names from the data files.

### Step 11: Perform Batch Deletions
- **Responsibility**: Programmer
   - Randomly remove a subset of names from both trees and count the operations involved.

### Step 12: Analyze Performance
- **Responsibility**: Programmer & ChatGPT
   - Compile the data from insertions, lookups, and deletions. Analyze and compare the results.
   - Consult ChatGPT if additional analysis or clarification is needed.

### Step 13: Create Graphs/Tables for Comparison
- **Responsibility**: Programmer
   - Generate graphs or tables to show comparative performance results.

### Step 14: Optional Stretch Goals
- **Responsibility**: Programmer & Copilot
   - Implement additional structures like AVL trees for advanced comparison.
   - Copilot can assist in generating the structure for the additional data structures.

---

## Evaluation Criteria
- Proper implementation of both binary search tree and red-black tree.
- Accurate instrumentation for counting operations.
- Clear comparison of results for both datasets.
- Effective use of Copilot and ChatGPT to assist, without relying solely on AI to complete the task.

---

Happy coding! Use AI to assist, but remember—**you** are the one in control of your code.

