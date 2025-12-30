# Employee Inheritance Project – Java

## Overview

This project demonstrates the concept of **inheritance and method overriding** in Java through a simple employee hierarchy. A base class `Employee` defines common employee information, while a derived class `Manager` extends it by adding department details and overriding behavior.

The project is designed to clearly show how inheritance promotes **code reuse**, **logical structure**, and **polymorphic behavior** in object-oriented programming.

---

## Project Description

The program includes:

* A base class **Employee** with basic employee information
* A derived class **Manager** that extends Employee
* Overridden methods to demonstrate runtime polymorphism
* A main class that creates objects of both classes and invokes their methods

---

## Features

* Demonstrates **inheritance** using `extends`
* Demonstrates **method overriding**
* Uses constructors and `super` keyword
* Clean and beginner-friendly Java code
* Console-based output for simplicity

---

## Class Structure

```
Employee
 ├─ name : String
 ├─ id : int
 ├─ basicSalary : double
 └─ displayInfo()

Manager (inherits Employee)
 ├─ department : String
 └─ displayInfo()  // overridden
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Inheritance-Employee-Hierarchy.git
```

2. Navigate to the project directory
3. Compile the program:

```bash
javac Main.java
```

4. Run the program:

```bash
java Main
```

---

## UML Class Diagram

The UML diagram shows:

* **Employee** as the base class
* **Manager** as a subclass inheriting from Employee
* Inheritance relationship represented by a hollow triangle arrow

*(UML diagram image included in the repository)*

---

## Technologies Used

* Java (Core Java)
* Object-Oriented Programming concepts

---

## Learning Outcome

Through this project, the following concepts are demonstrated:

* Inheritance in Java
* Method overriding
* Use of constructors and the `super` keyword
* Runtime polymorphism

---

## GitHub Repository

https://github.com/niazmahmud24434/Employee-Inheritance-Project

---
# Employee-Inheritance-Project
