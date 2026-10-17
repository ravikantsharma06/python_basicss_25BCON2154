Student Class Example 🐍

A simple Python program demonstrating the fundamentals of Object-Oriented Programming (OOP) by creating a Student class and storing student information such as name, roll number, and marks.

📌 Project Description

This project demonstrates how to define a Python class using the __init__() constructor and create an object from that class.

The program creates a Student object with the following information:

Name: Ravi
Roll Number: 101
Marks: 87.5

It then displays the student's details in a formatted output.

✨ Features
Demonstrates Python classes and objects
Uses the __init__() constructor
Stores student information using object attributes
Formats marks to one decimal place
Simple and beginner-friendly implementation
Requires no external libraries

2. Navigate to the project directory
cd your-repository
3. Run the program
python structure.py


📋 Requirements
Python 3.x
No external dependencies are required.

Check your Python version with:

python --version
🚀 Usage

Run the structure.py file from your terminal:

python structure.py

The program creates a Student object and prints its name, roll number, and marks.

💡 Example
Program
class Student:
    def __init__(self, name, roll, marks):
        self.name = name
        self.roll = roll
        self.marks = marks


s1 = Student("Ravi", 101, 87.5)

print("Name:", s1.name)
print("Roll:", s1.roll)
print("Marks: {:.1f}".format(s1.marks))
Output
Name: Ravi
Roll: 101
Marks: 87.5

📄 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this project according to the terms of the license.
