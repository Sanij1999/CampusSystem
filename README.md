# Campus System

A menu-driven Java console application that manages student records and campus route navigation using core data structures: Linked List, Stack, Queue, Binary Search Tree, Hash Table, and Graph.

**Module:** Data Structures and Algorithms (DSA) Group Assignment
**Institution:** SLTC

---

## Group Members

| No. | Name | Registration ID | Responsibility | Files |
|-----|------|-----------------|----------------|-------|
| 1 | [MI.Amnath Nadha] | [23DA2-0905] | Linked List & Student-Record Management | `Student.java`, `StudentLinkedList.java` |
| 2 | [AK.Sanij Kalees] | [23da2-0683] | Stack & Queue | `ActionStack.java`, `ServiceQueue.java` |
| 3 | [MR.Rishni Ruzaid] | [23da2-1114] | BST & Hashing | `StudentBST.java`, `StudentHashTable.java` |
| 4 | [TM HAKEEM] | [23DA2-0759] | Graph & BFS/DFS | `CampusGraph.java` |
| All | Whole group | - | Integration and final testing | `Main.java` |

---

## Individual Contributions

### Member 1 - [MI NADHA] (23DA2-0905])
- Implemented the `Student` class and the `StudentLinkedList`.
- Add, search, delete, and display student records.

### Member 2 - [AK.Sanij Kalees] ([23da2-0683])
- Implemented `ActionStack` for recent actions / undo history.
- Implemented `ServiceQueue` for processing student service requests in order.

### Member 3 - [MR.Rishni Ruzaid] ([23da2-1114])
- Implemented `StudentBST` for storing and searching students by ID.
- Implemented `StudentHashTable` (separate chaining) for fast lookup.

### Member 4 - [TM HAKEEM] ([23DA2-0759])
- Implemented `CampusGraph` using an adjacency list.
- Add locations, connect locations, and traverse with BFS and DFS.

### Integration
- `Main.java` combines all modules into one menu-driven application with input validation.

---

## Features

| Feature | Data Structure | Class |
|---------|----------------|-------|
| Student record management (add, search, delete, display) | Linked List | `StudentLinkedList` |
| Recent actions / undo history | Stack | `ActionStack` |
| Service request processing | Queue | `ServiceQueue` |
| Sorted storage and search by student ID | Binary Search Tree | `StudentBST` |
| Fast student lookup | Hash Table (separate chaining) | `StudentHashTable` |
| Campus locations and routes, BFS/DFS traversal | Graph (adjacency list) | `CampusGraph` |

---

## Project Structure

```
CampusSystem/
│   ├── Main.java
│   ├── Student.java
│   ├── StudentLinkedList.java
│   ├── ActionStack.java
│   ├── ServiceQueue.java
│   ├── StudentBST.java
│   ├── StudentHashTable.java
│   └── CampusGraph.java
├── .gitignore
└── README.md
```

---

## Requirements

- JDK 11 or higher
- VS Code with the *Extension Pack for Java* (optional), or any terminal

Check your installation:

```powershell
java -version
javac -version
```

---

## How to Compile and Run

### Windows (PowerShell)

```powershell
cd "path\to\CampusSystem"
mkdir bin
javac -d bin Main.java Student.java StudentLinkedList.java ActionStack.java ServiceQueue.java StudentBST.java StudentHashTable.java CampusGraph.java
java -cp bin Main
```

### Linux / macOS

```bash
mkdir -p bin
javac -d bin *.java
java -cp bin Main
```

### VS Code

1. Open the project folder in VS Code.
2. Open `Main.java`.
3. Click **Run** above the `main` method.

---

## Sample Usage

1. Choose the student records option and add students (for example `ST001`, `ST002`, `ST003`).
2. Search or delete a student by ID.
3. Add service requests to the queue and process them.
4. View recent actions from the stack.
5. Add campus locations (Main Gate, Library, Cafeteria, Auditorium), connect them, and run BFS / DFS.

---

## Submission

- GitHub repository: (https://github.com/Sanij1999/CampusSystem.git)

