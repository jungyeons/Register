
#  CS Project

This repository contains educational materials and code examples for understanding computer science concepts, 
including operating systems, networks, architecture, and system programming. It is organized into different 
directories based on topics.

## Table of Contents
1. [Directory Structure](#directory-structure)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Directory Structure

```
fastcampus-cs-main/
├── arch/        # Architecture-related files (e.g., encoding examples, documentation)
├── net/         # Network analysis files in PCAP format
├── os/          # Operating System code examples in C, Java, and Python
├── sql/         # SQL scripts for database operations
├── sys/         # System programming examples (e.g., multithreading, file handling)
```

### Key Directories and Files
- **arch**:
  - `README.md`: Documentation for architecture-related topics.
  - `encoding.py`: Python script for encoding demonstration.
  - `x86-64-reference.pdf`: Reference documentation for x86-64 architecture.

- **net**: Contains network packet capture files in `.pcap` and `.pcapng` formats, such as:
  - `3-way-handshake.pcap`: Demonstrates TCP 3-way handshake.
  - `fragmentation.pcapng`: Example of IP fragmentation.

- **os**: Examples and exercises for operating systems concepts, including:
  - `MultiThreadExample.java`: Multithreading example in Java.
  - `mulp*.c`: Various C programs related to OS-level operations.

- **sql**: SQL scripts for various operations:
  - `create_db_and_table.sql`: Script for database and table creation.
  - `select.sql`: Examples of SELECT queries.

- **sys**: System programming examples and utilities:
  - `file_*.c`: Examples of file handling in C.
  - `pipe_*.c`: Examples of inter-process communication using pipes.
  - `mmap_*.c`: Examples of memory mapping in C.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fastcampus-cs-main.git
   ```
2. Navigate to the desired directory to explore examples and exercises.

## Usage
- For Python scripts, use:
  ```bash
  python3 script_name.py
  ```
- For C programs, compile with `gcc`:
  ```bash
  gcc program.c -o program
  ./program
  ```
- For Java programs, compile with `javac`:
  ```bash
  javac Program.java
  java Program
  ```

## Contributing
Contributions are welcome! Please follow the standard [GitHub workflow](https://guides.github.com/introduction/flow/) to submit changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
