# Distributed Sorting & Vector Processing (Data Structures II)

Java implementation of a Client-Worker distributed processing model designed for parallel array manipulation, vector operations, and sorting algorithm execution.

## 🚀 Features

- **Client-Worker Architecture:** Multi-process distribution handling tasks between `Client`, `Worker0`, and `Worker1`.
- **Sorting Algorithms:** Implementation of array sorting techniques (`SortingAlgorithms.java`).
- **Vector Operations:** Helper utilities for array operations and data partitioning (`VectorUtils.java`).

## 🛠️ Built With

- **Language:** Java
- **Concepts:** Data Structures, Concurrency, Distributed Computing, Parallel Processing

## 📂 Project Structure

```text
Lab 3/
├── Client.java              # Client node coordinating tasks
├── Worker0.java             # Primary worker node processing data partitions
├── Worker1.java             # Secondary worker node processing data partitions
└── Util/
    ├── SortingAlgorithms.java # Sorting algorithms implementations
    └── VectorUtils.java      # Vector manipulation utilities
```

🚦 Getting Started
Prerequisites
Java Development Kit (JDK 8 or higher)

Compilation & Execution
Clone the repository:

Bash
git clone [https://github.com/Danielit707/Laboratorio-3-EDD-II.git](https://github.com/Danielit707/Laboratorio-3-EDD-II.git)
cd Laboratorio-3-EDD-II
Compile the source files:

Bash
javac "Lab 3/*.java" "Lab 3/Util/*.java"
Run the Client process:

Bash
java -cp "Lab 3" Client
