# Object Oriented Programming Lab

This repository contains the laboratory programs implemented as part of the **Object Oriented Programming (OOPS) using C++** course.

The purpose of this repository is to maintain a systematic record of the laboratory work and demonstrate the implementation of fundamental C++ programming and Object Oriented Programming concepts.

---

## Student Information

| **Field** | **Details** |
|---|---|
| **Name** | Kartik Siddaramayya Hiremath |
| **USN** | 01FE23BEC350 |
| **Roll Number** | 651|
| **Division** | F |
| **Semester** | 7th Semester |
| **Branch** | Electronics and Communication Engineering |
| **University** | KLE Technological University, Hubballi |

---

## About This Repository

The purpose of this repository is to maintain a systematic record of the **Object Oriented Programming laboratory work**.

Each program is written in **C++** and focuses on a specific programming concept. The programs progress from fundamental C++ concepts to Object Oriented Programming concepts such as classes, objects, constructors, destructors, static members, friend functions, and inheritance.

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
- Destructors

### Static Members

- Static data members
- Static member functions
- Static counters
- Sharing data among objects

### Friend Functions

- Friend functions
- Accessing private members using friend functions
- Friend functions involving multiple classes

### Inheritance

- Base and derived classes
- Single inheritance
- Multilevel inheritance
- Public inheritance
- Private inheritance
- Access control in inheritance
- Inheritance of member functions

---

## Programming Language

**C++**

---


# Laboratory Programs

The following programs are included in this repository.

## Chapter 1 – C++ Fundamentals

| **File** | **Description** |
|---|---|
| `Program_1.cpp` | Demonstrating fundamental data types such as `int`, `float`, and `char` |
| `Program_2.cpp` | Printing basic information using `cout` |
| `Program_3.cpp` | Accepting two numbers and displaying their sum |
| `Program_4.cpp` | Computing the area of a rectangle using user-provided length and breadth |
| `Program_5_Largest_element.cpp` | Finding the largest element in an array |
| `Program_6.cpp` | Determining the length of a C-style character array using `strlen()` |
| `Program_7.cpp` | Determining the length of a C++ string using the `length()` function |
| `Program_8 (Palindrome).cpp` | Checking whether a string is a palindrome |
| `Program_9 (Swap_two_numbers_Pass_by_value).cpp` | Demonstrating argument passing by value while swapping two numbers |
| `Program_10 (Swap_two_numbers_Pass_by_reference).cpp` | Demonstrating argument passing by reference while swapping two numbers |
| `Program_11 (Swap_two_numbers_Pass_by_pointer).cpp` | Demonstrating argument passing using pointers while swapping two numbers |


## Chapter 2 – Classes, Objects and OOP Features

| **File** | **Description** |
|---|---|
| `Program_12_class&object.cpp` | Creating a class and object to store and display student-related data |
| `Program_13_classes&objects.cpp` | Demonstrating classes and objects using a student class |
| `Program_14_Scope_resolution_class&objects.cpp` | Defining a member function outside the class using the scope resolution operator `::` |
| `Program_15_class_Rectangle.cpp` | Calculating the area of a rectangle using a class and member functions |
| `Program_16_student_scope_resolution.cpp` | Defining a member function outside the class and using the `this` pointer |
| `Program_17_class_time_for_2_objects.cpp` | Creating multiple objects of a `Time` class and displaying their values |
| `Program_18_passing_objects_as_fnx_arguments_add_time.cpp` | Passing objects as function arguments and adding two time objects |
| `Program_19_adding_two_complex_numbers.cpp` | Adding two complex numbers using objects and member functions |
| `Program_20_mileage_using_constructor.cpp` | Demonstrating a default constructor using a `Car` class |
| `Program_21_employee_constructor.cpp` | Demonstrating a default constructor using an `Employee` class |
| `Program_22_employee_parameterized_constructor.cpp` | Demonstrating a parameterized constructor using an `Employee` class |
| `Program_23_class_distance_parameterized.cpp` | Creating a `Distance` object using a parameterized constructor |
| `Program_24_class_rectangle_all_3_constructor.cpp` | Demonstrating default, parameterized, and copy constructors along with a destructor |
| `Program_25_static_data_members_demo.cpp` | Demonstrating a static data member shared among multiple objects |
| `Program_26_employee_static.cpp` | Using a static employee ID counter and demonstrating a destructor |
| `Program_27_static_member_fnx_count.cpp` | Demonstrating a static data member and static member function |
| `Program_28_Friend_fnx.cpp` | Using a friend function to access private data and calculate a sum |
| `Program_29_Friend_fnx_to_another_class.cpp` | Using a friend function to access private members of two different classes |

## Chapter 3 – Inheritance

| **File** | **Description** |
|---|---|
| `Program_30_Single_inheritance.cpp` | Demonstrating single inheritance using `Animal` and `Dog` classes |
| `Program_31_Multi-level_Inheritance.cpp` | Demonstrating multilevel inheritance using `Person`, `Student`, and `ITStudent` classes |
| `Program_32_Multi-level-Inheritance_vehicle_car_sports-car_as_classes.cpp` | Demonstrating multilevel inheritance using `Vehicle`, `Car`, and `SportsCar` classes |


## Repository Structure

```text
OOPS-Lab/
│
├── README.md
│
├── Chapter-1-C++-Fundamentals/
│   ├── 01_Basic_Data_Types/
│   ├── 02_Basic_Output/
│   ├── 03_Addition_of_Two_Numbers/
│   ├── 04_Rectangle_Area/
│   ├── 05_Largest_Element/
│   ├── 06_C_String_Length/
│   ├── 07_CPP_String_Length/
│   ├── 08_String_Palindrome/
│   ├── 09_Pass_By_Value/
│   ├── 10_Pass_By_Reference/
│   └── 11_Pass_By_Pointer/
│
├── Chapter-2-Classes-and-Objects/
│   ├── 12_Basic_Class_and_Object/
│   ├── 13_Student_Class_and_Object/
│   ├── 14_Scope_Resolution/
│   ├── 15_Rectangle_Using_Class/
│   ├── 16_Student_Scope_Resolution/
│   ├── 17_Time_Class/
│   ├── 18_Addition_of_Time_Objects/
│   ├── 19_Complex_Number_Addition/
│   ├── 20_Default_Constructor_Car/
│   ├── 21_Employee_Default_Constructor/
│   ├── 22_Employee_Parameterized_Constructor/
│   ├── 23_Distance_Parameterized_Constructor/
│   ├── 24_Constructors/
│   ├── 25_Static_Data_Member/
│   ├── 26_Employee_Static_Member/
│   ├── 27_Static_Member_Function/
│   ├── 28_Friend_Function/
│   └── 29_Friend_Function_Two_Classes/
│
└── Chapter-3-Inheritance/
    ├── 30_Single_Inheritance/
    ├── 31_Multilevel_Inheritance/
    └── 32_Multilevel_Inheritance_Vehicle/
```

---



## Repository Updates

This repository is maintained throughout the semester.

New laboratory programs and exercises will be added periodically as they are completed.


## Author

**Kartik Siddaramayya Hiremath**

Electronics and Communication Engineering  
KLE Technological University, Hubballi
