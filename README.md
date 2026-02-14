# 🗂️ Generalised Data Structure Library

A **C++ template-based library** implementing common data structures with generic programming. Supports **Singly & Doubly Linked Lists (linear & circular), Stack, and Queue** with all basic operations. Designed for **learning, testing, and real-world applications**.

---

## 🚀 Features

- **Singly Linear & Circular Linked List**  
  Insert, delete, and traverse at any position.
- **Doubly Linear & Circular Linked List**  
  Supports bidirectional traversal with insert/delete operations.
- **Stack**  
  Push, pop, peep, and display elements dynamically.
- **Queue**  
  Enqueue, dequeue, and display elements dynamically.
- **Generic Implementation**  
  Supports multiple data types (int, char, double, etc.) using templates.
- **Comprehensive Testing**  
  Sample `main()` demonstrates all operations for each data structure.

---

## 🛠️ Tech Stack

- **Language:** C++  
- **Concepts:** Templates, Linked Lists, Stacks, Queues, Circular & Doubly Linked Lists, Object-Oriented Programming

---

## 📌 Sample Usage

### Singly Linked List
```cpp
SinglyLLL<int> *obj = new SinglyLLL<int>();
obj->InsertFirst(10);
obj->InsertLast(20);
obj->Display();   // Output: | 10 |-> | 20 |-> NULL
delete obj;
