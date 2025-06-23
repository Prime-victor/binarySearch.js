# 🔍 Binary Search in JavaScript

This project demonstrates how to implement **Binary Search** in JavaScript — both **iterative** and **recursive** versions.

## 📌 What is Binary Search?

Binary Search is an efficient search algorithm that finds the position of a target value within a **sorted array**.  
It works by repeatedly dividing the search interval in half:

- If the target value is equal to the middle element — return the index.
- If the target value is less than the middle element — repeat the search on the left half.
- If the target value is greater than the middle element — repeat the search on the right half.

⏱️ **Time Complexity:** O(log n)  
🔢 **Space Complexity:**  
- Iterative: O(1)  
- Recursive: O(log n) due to the call stack

---

## 📄 Files

- **binarySearch.js**  
  Contains:
  - `binarySearchIterative(arr, target)`
  - `binarySearchRecursive(arr, target, left, right)`

---

## ⚙️ How to Run

1️⃣ Clone this repository or download the `binarySearch.js` file.

2️⃣ Open your terminal in the project directory.

3️⃣ Run the file using Node.js:
```bash
node binarySearch.js
