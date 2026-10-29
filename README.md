# School 42 C++ Modules 00-09

A complete collection of the C++ modules from the 42 School curriculum. This series introduces Object-Oriented Programming (OOP) concepts.

## Curriculum Overview

Each module focuses on specific C++ concepts, progressively building in complexity. From Module 02 onwards, all classes must be designed in the **Orthodox Canonical Form** (containing a default constructor, copy constructor, copy assignment operator, and destructor).

*   **CPP 00:** Namespaces, classes, member functions, stdio streams, initialization lists, static, const.
*   **CPP 01:** Memory allocation, pointers to members, references, file streams.
*   **CPP 02:** Ad-hoc polymorphism, operator overloading, Orthodox Canonical Class Form.
*   **CPP 03:** Inheritance.
*   **CPP 04:** Subtype polymorphism, abstract classes, interfaces.
*   **CPP 05:** Repetition and Exceptions handling.
*   **CPP 06:** C++ casts (`static_cast`, `dynamic_cast`, `reinterpret_cast`, `const_cast`).
*   **CPP 07:** C++ templates.
*   **CPP 08:** Templated containers, iterators, algorithms.
*   **CPP 09:** Standard Template Library (STL) practical applications.

## Compilation & Execution

Each module contains separate exercise directories (e.g., `ex00`, `ex01`). Navigate to a specific exercise folder to compile and run the program. 

1. Navigate to an exercise directory:
   ```bash
   cd cpp00/ex00
   ```
2. Compile the code:
   ```bash
   make
   ```
3. Run the generated executable (the executable name varies per exercise):
   ```bash
   ./<executable_name>
   ```

## Makefile Rules

* `make` - Compiles the executable.
* `make clean` - Removes object files (`.o`).
* `make fclean` - Removes object files and the executable.
* `make re` - Fully recompiles the program (`fclean` + `make`).
