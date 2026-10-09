Integer Addition Program

A simple, modular implementation of integer addition using the C programming language. This project demonstrates function-based programming, input validation, and basic software testing through a structured source-code organization.

About the Project

The Integer Addition Program performs addition on two integers entered by the user. The application is divided into separate source files to keep the implementation organized and make individual components easier to maintain and test.

Although addition is a fundamental arithmetic operation, this project provides an opportunity to understand how small C applications can be structured using reusable functions and separate testing logic.

Key Highlights

* Function-Based Implementation: Performs addition through a dedicated function.
* Modular Codebase: Organizes declarations, implementation, and tests into separate files.
* Input Verification: Checks whether the entered values are valid integers.
* Basic Error Handling: Handles unsuccessful input operations.
* Unit Testing: Uses assertions to verify expected arithmetic results.
* Portable Source Code: Can be compiled using a compatible C compiler.

Repository Layout

Integer-Addition/
├── Header/
│   └── Header.h
├── src/
│   ├── EntryPointFunction.c
│   └── MainFunction.c
├── Test/
│   └── AssertFunction.c
├── Doc/
└── Myexe.exe

Requirements

Before running the project, ensure that you have:

* A C compiler, such as GCC
* A terminal or command-line interface
* Basic knowledge of compiling C source files

Installation and Execution

Step 1: Clone the Repository

git clone <repository-url>

Navigate to the project directory:

cd Integer-Addition

Replace <repository-url> with the actual URL of your GitHub repository.

Step 2: Compile the Program

gcc src/MainFunction.c src/EntryPointFunction.c -o addition

Step 3: Execute the Program

For Linux and macOS:

./addition

For Windows:

addition.exe

Sample Execution

Enter first number:
15
Enter second number:
25
Addition is :40

Output: The program calculates and displays the sum of the two supplied integers.

Testing

The project contains a separate test file that uses the C assert() mechanism to verify the addition function.

Compile the test program independently:

gcc Test/AssertFunction.c src/EntryPointFunction.c -o test_addition

Execute the generated test program:

./test_addition

If all assertions pass, the program completes without an assertion failure.

Concepts Demonstrated

This project reinforces several fundamental software development concepts:

1. Function declaration and definition in C
2. Header files and source-file organization
3. Integer input and output operations
4. Input validation and error handling
5. Assertions and basic testing practices
6. Compilation of multi-file C programs

Potential Enhancements

The project can be extended in several ways:

* Implement additional arithmetic operations.
* Add comprehensive test cases for edge conditions.
* Handle integer overflow explicitly.
* Introduce a Makefile to simplify compilation.
* Integrate automated builds and tests into a CI pipeline.

Author

Sanjana Vinod Hiwrale

⸻

Language: C
Category: Beginner Programming / Software Development
Project Type: Command-Line Application
