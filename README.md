# Student-management-system


student-management-system-cpp
A simple Student Management System built in C++ using object-oriented programming principles.
# Student Management System in C++

A simple console-based Student Management System written in C++ using Object-Oriented Programming (OOP) concepts.

## 🚀 Features

- Add new students
- View student details
- Update student records
- Delete student records
- Display all students
- Menu-driven interface

## 🛠️ Technologies Used

- C++
- Standard Template Library (STL)
- File I/O (for data persistence, if implemented)

## 📸 Screenshot

*(Add a screenshot here if your program has a UI or terminal interface output)*

## 📂 Project Structure




#include <iostream>
#include <vector>
#include <algorithm>

using namespace std;

class Student {
private:
    int rollNo;
    string name;
    string course;

public:
    void input() {
        cout << "Enter Roll Number: ";
        cin >> rollNo;
        cin.ignore(); // clear buffer
        cout << "Enter Name: ";
        getline(cin, name);
        cout << "Enter Course: ";
        getline(cin, course);
    }

    void display() const {
        cout << "Roll No: " << rollNo << "\n";
        cout << "Name: " << name << "\n";
        cout << "Course: " << course << "\n";
        cout << "--------------------

