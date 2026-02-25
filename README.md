# UseCase8 – Linked List Based Palindrome Checker

## 🧠 Objective
Validate whether a string is a palindrome using a Singly Linked List with in-place reversal.

---

## 🎯 Goal
Convert a string into a linked list, reverse the second half of the list, and compare both halves to determine whether the string is a palindrome.

---

## 🔄 Flow of Execution

1. Convert the input string into a singly linked list  
2. Use Fast and Slow pointers to find the middle  
3. Reverse the second half of the linked list in-place  
4. Compare the first half and reversed second half  
5. Display the result  

---

## 📚 Key Concepts Used

### Singly Linked List
A dynamic data structure where each node contains data and a reference to the next node.

### Node Traversal
Sequential access to elements using the `next` reference.

### Fast and Slow Pointer Technique
Used to efficiently locate the middle of the linked list.

### In-Place Reversal
Reverses the second half of the list without using extra memory.

---

## 🛠 Data Structure Used
- Singly Linked List

---

## ⚙️ How to Run

### Compile:
```
javac UseCase8PalindromeCheckerApp.java
```

### Run:
```
java UseCase8PalindromeCheckerApp
```

---

## 📌 Example

### Input
```
level
```

### Output
```
Input : level
Is Palindrome? : true
```

---

## 🚀 Learning Outcome

This implementation demonstrates:

- Efficient palindrome validation using linked lists  
- Optimal space usage (O(1) extra space)  
- Middle detection using fast/slow pointers  
- In-place list manipulation  

---

## 👨‍💻 Author

Dito Dileep  
B.Tech Computer Science (AI & ML)  
SRM Institute of Science and Technology
