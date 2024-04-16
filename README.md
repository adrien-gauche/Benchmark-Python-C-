Matrix Multiplication Performance Comparison
=============================================

This repository contains C and Python implementations of matrix multiplication, along with a Bash script to run both implementations. The purpose of this comparison is to analyze the performance of each language in terms of execution time for this specific operation.

Files
-----

* `MatrixMultiplication.c`: C implementation of matrix multiplication.
* `MatrixMultiplication.py`: Python implementation of matrix multiplication.
* `execute.sh`: Bash script to compile and run the C program and run the Python script.

Requirements
------------

* For C: A C compiler (such as GCC) and a Unix-like environment (such as Linux or macOS) or Windows with MinGW installed.
* For Python: Python interpreter (version 3.x recommended) and a Unix-like environment (such as Linux or macOS) or Windows.
* For the Bash script: A Unix-like environment (such as Linux or macOS) or Windows with Git Bash installed.

Usage
-----

### Using the Bash script (execute.sh)

1. Make the script executable:
```bash
chmod +x execute.sh
```
2. Run the script:
```bash
./execute.sh
```
The output will display the elapsed time in seconds for the matrix multiplication operation in both C and Python implementations.

### C (manual)

1. Compile the C code:
```c++
gcc MatrixMultiplication.c -o matrix
```
2. Run the executable:
```bash
./matrix
```
The output will display the elapsed time in seconds for the matrix multiplication operation.

### Python (manual)

Run the Python script:
```bash
python MatrixMultiplication.py
```
The output will display the elapsed time in seconds for the matrix multiplication operation.

Performance Comparison
----------------------

The performance comparison between C and Python for matrix multiplication is discussed in the following article:

[A Performance Comparison Between C, Java, and Python](https://medium.com/swlh/a-performance-comparison-between-c-java-and-python-df3890545f6d)

The article provides insights into the execution time differences between the two languages and discusses factors that contribute to these differences.

License
-------

This project is licensed under the [MIT License](LICENSE).