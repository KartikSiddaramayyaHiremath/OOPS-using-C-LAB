# Object Oriented Programming Lab

This repository contains the laboratory programs implemented as part of the **Object Oriented Programming (OOPS) using C++** course.

The purpose of this repository is to maintain a systematic record of the laboratory work and demonstrate the implementation of fundamental C++ programming and Object Oriented Programming concepts.

---

## Student Information

| **Field** | **Details** |
|---|---|
| **Name** | Kartik Siddaramayya Hiremath |
| **USN** | 01FE23BEC350 |
| **Roll Number** | 651 |
| **Division** | F |
| **Semester** | 7th Semester |
| **Branch** | Electronics and Communication Engineering |
| **University** | KLE Technological University, Hubballi |

---

## About This Repository

The purpose of this repository is to maintain a systematic record of the **Object Oriented Programming laboratory work**.

Each program is written in **C++** and focuses on a specific programming concept. The programs progress from fundamental C++ concepts to Object Oriented Programming concepts such as classes, objects, constructors, destructors, static members, friend functions, inheritance, polymorphism, operator overloading, and exception handling.

The repository is organized chapter-wise to make the programs easier to understand, access, and practice.

The repository will be updated regularly as new laboratory programs and concepts are completed.

---

## Learning Areas

The laboratory work in this repository focuses on understanding and implementing the following concepts using C++.

### Fundamental Programming Concepts

- C++ program structure
- Standard input and output
- Variables and data types
- Arithmetic operations
- Conditional statements
- Arrays
- C-style strings
- C++ strings
- String manipulation
- Functions
- Pass by value
- Pass by reference
- Pass by pointer

### Classes and Objects

- Classes and objects
- Data members and member functions
- Encapsulation
- Public and private members
- Scope resolution operator
- Member functions defined outside the class
- `this` pointer
- Passing objects as function arguments

### Constructors and Destructors

- Default constructors
- Parameterized constructors
- Copy constructors
- Constructor overloading
- Constructor initializer lists
- Destructors

### Static Members and Friend Functions

- Static data members
- Static member functions
- Static counters
- Sharing data among objects
- Friend functions
- Accessing private members using friend functions
- Friend functions involving multiple classes

### Inheritance

- Base and derived classes
- Single inheritance
- Multilevel inheritance
- Multiple inheritance
- Virtual base classes
- Diamond problem
- Constructor initialization in inheritance

### Polymorphism

- Compile-time and runtime polymorphism
- Virtual functions
- Pure virtual functions
- Abstract classes
- Function overriding

### Operator Overloading

- Binary operator overloading
- Addition operator overloading
- Subtraction operator overloading
- Unary increment operator overloading
- Unary decrement operator overloading
- String concatenation using operator overloading

### Exception Handling

- `try`, `throw`, and `catch`
- Handling different exception types
- Division-by-zero exceptions
- Nested try-catch blocks
- Catch-all exception handling
- Exception handling with arguments

---

## Programming Language

**C++**

---

# Laboratory Programs

The following programs are included in this repository.

## Chapter 1 – C++ Fundamentals (Programs 1–11)

| **File** | **Description** |
|---|---|
| `01_Program_1.cpp` | Demonstrating fundamental data types such as `int`, `float`, and `char` |
| `02_Program_2.cpp` | Printing basic information using `cout` |
| `03_Program_3.cpp` | Accepting two numbers and displaying their sum |
| `04_Program_4.cpp` | Computing the area of a rectangle using user-provided length and breadth |
| `05_Program_5_Largest_element.cpp` | Finding the largest element in an array |
| `06_Program_6.cpp` | Determining the length of a C-style character array using `strlen()` |
| `07_Program_7.cpp` | Determining the length of a C++ string using the `length()` function |
| `08_Program_8 (Palindrome).cpp` | Checking whether a string is a palindrome |
| `09_Program_9 (Swap_two_numbers_Pass_by_value).cpp` | Demonstrating argument passing by value while swapping two numbers |
| `10_Program_10 (Swap_two_numbers_Pass_by_reference).cpp` | Demonstrating argument passing by reference while swapping two numbers |
| `11_Program_11 (Swap_two_numbers_Pass_by_pointer).cpp` | Demonstrating argument passing using pointers while swapping two numbers |

## Chapter 2 – Classes, Objects and OOP Features (Programs 12–29)

| **File** | **Description** |
|---|---|
| `12_Program_12_class&object.cpp` | Creating a class and object to store and display student-related data |
| `13_Program_13_classes&objects.cpp` | Demonstrating classes and objects using a student class |
| `14_Program_14_Scope_resolution_class&objects.cpp` | Defining a member function outside the class using the scope resolution operator `::` |
| `15_Program_15_class_Rectangle.cpp` | Calculating the area of a rectangle using a class and member functions |
| `16_Program_16_student_scope_resolution.cpp` | Defining a member function outside the class and using the `this` pointer |
| `17_Program_17_class_time_for_2_objects.cpp` | Creating multiple objects of a `Time` class and displaying their values |
| `18_Program_18_passing_objects_as_fnx_arguments_add_time.cpp` | Passing objects as function arguments and adding two time objects |
| `19_Program_19_adding_two_complex_numbers.cpp` | Adding two complex numbers using objects and member functions |
| `20_Program_20_mileage_using_constructor.cpp` | Demonstrating a default constructor using a `Car` class |
| `21_Program_21_employee_constructor.cpp` | Demonstrating a default constructor using an `Employee` class |
| `22_Program_22_employee_parameterized_constructor.cpp` | Demonstrating a parameterized constructor using an `Employee` class |
| `23_Program_23_class_distance_parameterized.cpp` | Creating a `Distance` object using a parameterized constructor |
| `24_Program_24_class_rectangle_all_3_constructor.cpp` | Demonstrating default, parameterized, and copy constructors along with a destructor |
| `25_Program_25_static_data_members_demo.cpp` | Demonstrating a static data member shared among multiple objects |
| `26_Program_26_employee_static.cpp` | Using a static employee ID counter and demonstrating a destructor |
| `27_Program_27_static_member_fnx_count.cpp` | Demonstrating a static data member and static member function |
| `28_Program_28_Friend_fnx.cpp` | Using a friend function to access private data and calculate a sum |
| `29_Program_29_Friend_fnx_to_another_class.cpp` | Using a friend function to access private members of two different classes |

## Chapter 3 – Inheritance (Programs 30–38)

| **File** | **Description** |
|---|---|
| `30_Program_30_Single_inheritance.cpp` | Demonstrating single inheritance using `Animal` and `Dog` classes |
| `31_Program_31_Multi-level_Inheritance.cpp` | Demonstrating multilevel inheritance using `Person`, `Student`, and `ITStudent` classes |
| `32_Program_32_Multi-level-Inheritance_vehicle_car_sports-car_as_classes.cpp` | Demonstrating multilevel inheritance using `Vehicle`, `Car`, and `SportsCar` classes |
| `33_Program_33_Constructor_initializer_list.cpp` | Demonstrating constructor initializer lists in inheritance |
| `34_Program_34_Constructor_initializer_list_multi_level_inheritance.cpp` | Using constructor initializer lists in multilevel inheritance |
| `35_Program_35_Multiple_inheritance.cpp` | Demonstrating multiple inheritance |
| `36_Program_36_GTU_Program_class_student_multiple_inheritance.cpp` | Demonstrating multiple inheritance using student-related classes |
| `37_Program_37_without_virtual.cpp` | Demonstrating the diamond problem without virtual inheritance |
| `38_Program_38_Virtual.cpp` | Using virtual base classes to solve the diamond problem |

## Chapter 4 – Polymorphism and Operator Overloading (Programs 39–47)

| **File** | **Description** |
|---|---|
| `39_Program_39_Polymorphism_Virtual_function.cpp` | Demonstrating runtime polymorphism using virtual functions |
| `40_Program_40_Polymorphism_class_shape.cpp` | Demonstrating polymorphism using a `Shape` class and derived classes |
| `41_Program_41_Poly_multiple_shapes.cpp` | Demonstrating polymorphism using multiple shape classes |
| `42_Program_42_Pure_virtual_fnx.cpp` | Demonstrating pure virtual functions and abstract classes |
| `43_Program_43_Operator_overloading_addition.cpp` | Overloading the addition operator for complex number addition |
| `44_Program_44_Operator_overloading_subtraction.cpp` | Overloading the subtraction operator |
| `45_Program_45_Operator_overloading_unary_increment.cpp` | Overloading the unary increment operator |
| `46_Program_46_Operator_overloading_unary_decrement.cpp` | Overloading the unary decrement operator |
| `47_Program_47_Concatenate_two_strings.cpp` | Demonstrating string concatenation using operator overloading |

## Chapter 5 – Exception Handling (Programs 48–57)

| **File** | **Description** |
|---|---|
| `48_Program_48_Exception_Handling_1.cpp` | Introduction to exception handling using `try`, `throw`, and `catch` |
| `49_Program_49_Exception_Handling_2.cpp` | Demonstrating exception handling for multiplication conditions |
| `50_Program_50_Exception_Handling_3.cpp` | Handling different exception types |
| `51_Program_51_Exception_Handling_4.cpp` | Demonstrating division-by-zero exception handling |
| `52_Program_52_Exception_Handling_5.cpp` | Demonstrating exception handling using division operations |
| `53_Program_53_Excpetion_Handling_Voting_Condition.cpp` | Checking voting eligibility using exception handling |
| `54_Program_54_Exception_Handling_Calculator.cpp` | Performing calculator operations with exception handling |
| `55_Program_55_Catch_all_block.cpp` | Demonstrating a catch-all exception handler |
| `56_Program_56_nested_try.cpp` | Demonstrating nested try-catch blocks |
| `57_Program_57_Exception_with_arguments.cpp` | Demonstrating exception handling with arguments |

---

## Repository Structure

```text
OOPS-Lab/
│
├── README.md
│
├── Chapter-1-C++-Fundamentals/
│   ├── 01_Program_1.cpp
│   ├── 02_Program_2.cpp
│   ├── ...
│   └── 11_Program_11 (Swap_two_numbers_Pass_by_pointer).cpp
│
├── Chapter-2-Classes-and-Objects/
│   ├── 12_Program_12_class&object.cpp
│   ├── 13_Program_13_classes&objects.cpp
│   ├── ...
│   └── 29_Program_29_Friend_fnx_to_another_class.cpp
│
├── Chapter-3-Inheritance/
│   ├── 30_Program_30_Single_inheritance.cpp
│   ├── ...
│   └── 38_Program_38_Virtual.cpp
│
├── Chapter-4-Polymorphism-and-Operator-Overloading/
│   ├── 39_Program_39_Polymorphism_Virtual_function.cpp
│   ├── ...
│   └── 47_Program_47_Concatenate_two_strings.cpp
│
└── Chapter-5-Exception-Handling/
    ├── 48_Program_48_Exception_Handling_1.cpp
    ├── ...
    └── 57_Program_57_Exception_with_arguments.cpp
```

---

## Notes

- Each program is maintained as a separate C++ source file.
- Programs are organized according to their respective chapters.
- The repository is intended for learning and practicing Object Oriented Programming concepts.
- Some programs demonstrate multiple related concepts in a single implementation.
- Compiled executable files are not required; the repository primarily maintains C++ source code.

---

## Repository Updates

This repository is maintained throughout the semester.

New laboratory programs and exercises will be added periodically as they are completed.

---

## Author

**Kartik Siddaramayya Hiremath**

Electronics and Communication Engineering  
KLE Technological University, Hubballi
