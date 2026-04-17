# Smart Restaurant Management System (SRMS)
### Data Structure Lab Project – Binary Brains

---

## 1. Executive Summary
The **Smart Restaurant Management System (SRMS)** is a console-based restaurant management application developed in **ANSI C** as part of the **CSE124: Data Structure Lab** course at **Daffodil International University (DIU)**. 

This system operationalizes core data-structure concepts—including **singly linked lists, queues, nested nodes, dynamic memory management, and file persistence**—to simulate real-world restaurant workflow automation.

The project includes two operational modes:
* **Manager Mode:** Full administrative access with menu CRUD operations, stock management, order queue handling, and order serving.
* **Customer Mode:** Guided interface for browsing the menu and placing table-wise orders.

---

## 2. Group Information
**Group Name:** Binary Brains  
**Leader:** * Sk. Azmain Zunaeid (251-15-222)

**Members:**
* Md. Delower Sarker (251-15-457)
* Md. Maruf Mia (251-15-042)
* Syeda Zawada Farah (251-15-223)
* Maher Afruz Mira (251-15-017)

---

## 3. Academic Information
* **Program:** Bachelor of Science in Computer Science and Engineering (CSE)
* **Course Code:** CSE124
* **Course Title:** Data Structure Lab
* **Semester:** Fall 2025
* **Section:** 68_A1
* **Course Instructor:** Mr. Md. Jakaria Zobair (Lecturer)
* **University:** Daffodil International University (DIU)

---

## 4. System Description

### 4.1 Menu Management Module (Singly Linked List)
* Stores menu items dynamically using a linked list.
* Allows full CRUD operations: **Insert** (Beginning, Last, After a Specific ID), **Delete** (First, Last, Specific ID), **Update**, **Search**, **Count**.
* Validates duplicate IDs and names.
* Ensures persistent storage through `menu.txt`.

### 4.2 Order Processing Module (Queue + Nested Linked Lists)
* Uses a **queue** to maintain pending orders in FIFO (First-In-First-Out) order.
* Each order node contains a **nested linked list** of ordered items.
* Supports bill calculation and systematic order serving.

### 4.3 User Interface Module
* **Manager Mode:** Password-protected access, menu management, pending-order viewing, and order serving.
* **Customer Mode:** Table selection, menu browsing, and item ordering.
* Strong input validation and error handling for seamless operation.

---

## 5. Key Features
* **Role-Based Access:** Manager & Customer workflows.
* **Persistent Storage:** Auto-saving and loading of menu data.
* **Stock Management:** Decreases stock automatically on order.
* **Queue-Based Order Handling:** Ensures fairness and operational discipline.
* **Robust Validation:** Prevents inconsistent or duplicate data entry.
* **Modular Structure:** Clean, scalable ANSI C design.

---

## 6. System Architecture
The architecture consists of:
1.  **Singly Linked List** for menu structure.
2.  **Queue** for table-wise pending orders.
3.  **Nested Linked Lists** for item-level order details.
4.  **File I/O Layer** ensuring persistence.
5.  **User Mode Controller** managing workflows.

---

## 7. Technologies and Concepts

| Component | Technology / Concept |
| :--- | :--- |
| **Language** | ANSI C |
| **Data Structures** | Linked List, Queue, Nested Nodes |
| **Storage** | Text File (`menu.txt`) |
| **Concepts** | Pointers, File Handling, Dynamic Memory Allocation |
| **Tools** | GCC, Visual Studio Code |
| **Platforms** | Windows / Linux |

---

