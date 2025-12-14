# Internship Evaluation – Practical Exam

Instructions:
1. Write solution inside src folder
2. Use any one language: C / C++ / Java / Python
3. Add comment block with Name, Enrollment, Logic
4. Push final code before time ends


# Internship Evaluation – Library Management System (2025–2026)

## Objective
Design and develop a console-based **Library Management System** that allows a librarian
to manage book records efficiently.

This problem statement is **language-independent** and can be implemented using:
- C
- C++
- Java
- Python

The objective is to evaluate core programming concepts such as control structures,
functions/methods, searching, sorting, logical deletion, authentication, and file handling.

---
## Functional Requirements

### 1. Add Book
- Add new book details:
  - Book ID
  - Title
  - Author
  - Quantity
  - Price
- Duplicate Book IDs must **not** be allowed.

---

### 2. Display All Books
- Display **only active books**
- Provide sorting options:
  1. Sort by Book ID
  2. Sort by Book Title

---

### 3. Search Book
Search a book only if it is **active**.

Use **nested switch** logic:

1 → Search by Book ID  
2 → Search by Book Title  

---

### 4. Issue Book
- Issue a book only if quantity is available
- Reduce the quantity after issuing

---

### 5. Return Book
- Increase the quantity of the returned book

---

### 6. Delete Book (Logical Deletion)
Delete a book **logically**, not physically.

Use an **active flag** to mark the book as inactive.

Use **nested switch** logic:

1 → Delete by Book ID  
2 → Delete by Book Title  

---

### 7. Exit
- Safely terminate the program

---

## Sample Menu

===== LIBRARY MANAGEMENT SYSTEM =====  
1. Add Book  
2. Display All Books  
3. Search Book By Id  
4. Issue Book  
5. Return Book  
6. Delete Book By Id  
7. Exit  

---

## Implementation Notes (Important)

- The mentioned data structures, classes, and logic are **guidelines only**
- Students are free to use **any valid approach**
- Any solution that fulfills all functional requirements correctly will be accepted

---

## Technical Rules

- Console-based application only
- No external frameworks
- Proper use of:
  - Functions / Methods
  - Classes / Structures
- Clean, readable, and modular code
- File handling must be used for data persistence

---

## Concepts Expected to be Used

- Structure / Class
- Arrays / Dynamic Arrays / Lists
- Functions / Methods
- Conditional statements (if, else, switch)
- Looping (for, while, do-while)
- String handling
- Linear search
- Sorting (Bubble sort or built-in)
- Logical deletion (active flag)
- Menu-driven programming
- User authentication
- Encapsulation (for OOP languages)
- File I/O

---

## Submission Instructions

1. Accept the GitHub Classroom assignment link
2. Clone your private repository
3. Implement the solution
4. Commit and push **only final working code**
5. Late commits will not be considered

---

## Evaluation Criteria

- Correct implementation of all requirements
- Proper authentication logic
- File handling usage
- Code clarity and structure
- Successful execution

---
