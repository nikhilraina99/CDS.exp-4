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
// Nikhil
// 23070123093
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

```javascript
// Nikhil
// 23070123093
#include <iostream>
#include <bitset>
using namespace std;

int main() {
    int num, set, reset;
    
    cout << "Enter the number- ";
    cin >> num;
    cout << "Enter the bit position to set (0 to 7): ";
    cin >> set;
    cout << "Enter the bit position to reset (0 to 7): ";
    cin >> reset;
    cout<<num<<" in binary is "<<bitset<8>(num)<<endl;
   
    int num_set = num | (1 << set);
    cout << "Result after setting bit number " <<set<< " is " << bitset<8>(num_set) << endl;
    
    int num_reset = num_set & ~(1 << reset);
    cout << "Result after resetting bit number " <<reset<< " is " << bitset<8>(num_reset) << endl;
    return 0;
}
```

## Output
1.

![Screenshot 2024-08-16 010507](https://github.com/user-attachments/assets/9d43a879-87f0-4529-b793-67340c3a8a80)

2.

![Screenshot 2024-08-23 004002](https://github.com/user-attachments/assets/87cd686a-b542-401c-b419-97e5ee328c12)

## Conclusion
This project demonstrates how to use bitwise operators in C++. Understanding these operators is essential for low-level data manipulation and optimization in programming.











