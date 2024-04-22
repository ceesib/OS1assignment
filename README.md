Description
This Java program performs memory address translation using a page table approach, where virtual addresses are translated into physical addresses using a predefined page table. The algorithm reads a binary file, converts its contents into little endian binary strings, translates virtual addresses into physical addresses based on the page table, and writes the physical addresses to an output file.

Author
Author: Ceejay Sibeko
Student Number: SBKCEE001

Prerequisites
Java Development Kit (JDK) installed

Building the Program
Open a terminal or command prompt and navigate to the directory containing the OS1Assignment.java file.

Compile the program by running the following command:
javac OS1Assignment.java
This will generate a file named OS1Assignment.class.

Running the Program
Run the program by executing the following command:
java OS1Assignment.java OS1sequence
The program will generate an output file named output-OS1 containing the physical addresses in hexadecimal format, one address per line.

Error Handling
The program checks for the following errors:
Missing input file: If the program is not provided with an input file as an argument, it will print an error message and exit.
File reading errors: If an error occurs while reading the input file, the program will print an error message and exit.
File writing errors: If an error occurs while writing the output file, the program will print an error message and exit.

Code Structure
The program consists of a single class named OS1Assignment with a main method. The main method performs the following tasks:
Reads the input file and stores the virtual addresses as a list of integers.
Converts the integers to little endian binary strings.
Performs memory address translation to generate physical addresses.
Writes the physical addresses to an output file.
