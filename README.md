# Experiment 4
## Aim
To explore and understand the use of bitwise operators in C++.
## Software Used
VS Code
## Problem Statement
Write a C++ program to demonstrate and explain various bitwise operations.
## Theory
Bitwise operators manipulate integers at the binary level. These operators handle bits directly, allowing for efficient data manipulation. Key bitwise operators include:

AND (&): Bitwise AND of two integers.
OR (|): Bitwise OR of two integers.
XOR (^): Bitwise XOR of two integers.
NOT (~): Bitwise NOT (complement) of an integer.
Left Shift (<<): Shifts bits to the left.
Right Shift (>>): Shifts bits to the right

## Program Codes
```javascript
#include<iostream>
#include<bitset>
using namespace std;
int main()
{
    int a,b;
    cout<<"Enter first number: ";
    cin>>a;
    cout<<"Enter second number: ";
    cin>>b;
    cout<<"a|b: "<<bitset<4>(a|b)<<endl;
    cout<<"a&b: "<<bitset<4>(a&b)<<endl;
    cout<<"a<<b: "<<bitset<4>(a<<b)<<endl;
    cout<<"ab: "<<bitset<4>(a>>b)<<endl;
    cout<<"~b: "<<bitset<4>(~b)<<endl;
    cout<<"a^b: "<<bitset<4>(a^b)<<endl;
    return 0;
}
```
## Output









