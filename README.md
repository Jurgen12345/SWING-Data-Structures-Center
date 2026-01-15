# SWING Data Structures Center

# *Project Overview*
  SWING Data Structures Center is a Java Swing–based application designed to deepen understanding of fundamental data structures by implementing them from scratch as modular, task-focused components within a unified desktop application.
The project incorporates several core data structures, including tree-based file searching, key–value (dictionary/map) search mechanisms, and queue-based task processing. Each feature is implemented as a standalone mini-application, allowing users to interactively explore how these data structures operate in practice.
In addition to its algorithmic focus, the application features a robust and responsive user interface, employing automatic resizing with consistent use of margins and padding to ensure usability across different window sizes.

<p align="center">
  <img src="Screenshot%202026-01-15%20095633.png" width="300">
</p>

## *Topic Editor*
  Topic Editor is a text editor that supports undo and redo operations, split views, and word search functionality. The application leverages multiple custom data structures—including Array, GenericArray, ObjectArray, StringArray, and IntegerArray—to efficiently manage text manipulation and editor operations.
By combining these data structures, the project demonstrates how foundational data structures can be applied to build practical, feature-rich software systems.

<p align="center">
  <img src="Screenshot%202026-01-15%20095829.png" width="400">
</p>

## *Help Center*
  Help Center is an application that simulates a call center environment in which incoming calls exceed the number of available operators. To manage this imbalance efficiently, the system uses a queue-based call handling mechanism, ensuring that callers are served on a first-in, first-out (FIFO) basis.
Incoming callers are placed into a queue and are automatically routed to customer support as operators become available. The caller profiles used in the simulation are predefined for demonstration purposes; however, the underlying design supports easy extension to accommodate custom or dynamically generated callers. This project illustrates how queue data structures can be applied to real-world service and scheduling scenarios.

<p align="center">
  <img src="Screenshot%202026-01-15%20095846.png" width="400">
</p>

## *File Base*
  File Base implements a binary search tree (BST)–based approach to efficiently index and search files within a selected directory. The system organizes file metadata—including file name, size, identifier, and other general attributes—into a tree structure, enabling fast lookup and retrieval operations.
Under balanced conditions, file searches achieve O(log n) time complexity, with a worst-case complexity of O(n) in unbalanced scenarios. This design demonstrates how tree-based data structures can be applied to build a high-performance file search system while preserving extensibility for additional file attributes.

<p align="center">
  <img src="Screenshot%202026-01-15%20095913.png" width="400">
</p>

## *KMS (Key Management System)*
The KMS module is a dictionary-based key–value system designed to demonstrate advanced data-structure concepts beyond simple mappings.

It allows users to store sequences of words as keys and associate them with corresponding values.
To enable efficient lookup and partial matching, the system organizes keys into tree-like substructures, where each segment of a word sequence contributes to a hierarchical search path.
Using this approach, the KMS can:
Insert key–value pairs where keys consist of multiple tokens
Traverse subtrees to determine whether a given key sequence represents a valid value
Perform fast key lookups without relying on built-in map or hash structures
Demonstrate how dictionary and tree concepts can be combined for structured searches
This module serves as a practical example of how custom dictionary implementations can be extended with tree-based traversal logic to support more complex key-matching scenarios.

<p align="center">
  <img src="Screenshot%202026-01-15%20095949.png" width="400">
</p>
 
