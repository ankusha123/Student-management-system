# Student-management-system
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

