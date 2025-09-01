# PythonProject1_UnitConverter_CLI

Unit Converter (CLI) – Python Project 4

This project is a Command-Line Interface (CLI) Unit Converter implemented in multiple ways to explore both procedural and Object-Oriented Programming (OOP) approaches in Python. It demonstrates how the same functionality can be structured using functions, instance methods, class methods, and static methods, helping learners understand the versatility and power of OOP concepts in real-world applications.

The unit converter supports the following conversions:

Kilometers ⇆ Miles

Celsius ⇆ Fahrenheit

Project Structure

PythonProgramming_PythonProject4_Unit_Converter(CLI).ipynb

A simple function-based approach.

Each conversion (km-to-miles, miles-to-km, c-to-f, f-to-c) is defined as an independent function.

A menu-driven CLI program calls the respective function based on user input.

PythonProgramming_PythonProject4_Unit_Converter(CLI)_ImplementingOOPsConcept.ipynb

Implements OOP using instance methods.

Defines a UnitConverter class where each conversion is performed by methods that operate on the instance variable value.

Demonstrates encapsulation and method binding with objects.

PythonProgramming_PythonProject4_Unit_Converter(CLI)_ImplementingOOPsConcept_UsingStaticMethod.ipynb

Showcases OOP with static methods.

Conversion methods don’t rely on instance attributes but are grouped inside a class for better organization.

Illustrates when to use @staticmethod in Python.

PythonProgramming_PythonProject4_Unit_Converter(CLI)_ImplementingOOPsConcept_UsingClassMethod.ipynb

Demonstrates OOP with class methods.

Uses @classmethod to perform conversions where methods are tied to the class itself rather than instances.

Useful for scenarios where shared logic applies across all objects.

Key Learning Outcomes

Function vs OOP Design: Understand the difference between standalone functions and class-based design.

Encapsulation: Learn how data can be encapsulated within classes using instance variables.

Static vs Class Methods: Explore when to use static methods (no access to instance/class data) versus class methods (access to class-level logic).

Practical CLI Program: Gain experience in writing interactive Python programs that accept user input and provide formatted output.

This project is ideal for beginners transitioning from basic Python functions to Object-Oriented Programming, offering a step-by-step comparison of different implementations of the same problem.
