# Experiment-15
## AIM
To learn about exception handling in c++.

## Problem Statement
1.) Write a c++ program to get a customized error for entering a negative number.

2.) Write a c++ program to get a customized error for entering a year less than 2000.

## Theory
In C++, exceptions are errors or unexpected conditions that arise during program execution, disrupting the normal flow of operations. Exception handling is a mechanism that allows programmers to manage these errors effectively by transferring control from the point of error to a designated error-handling block of code.

This approach helps maintain program stability, as it enables developers to address issues without crashing the entire application. By using try-catch blocks, programmers can anticipate potential errors and define appropriate responses, ensuring that the program can continue running smoothly and handle exceptional situations gracefully. This makes exception handling an essential feature in C++ for creating robust and reliable applications.

## CODES-
1)
```javascript
//Sharvari Murade
//23070123088
#include<iostream>
using namespace std;
 int main()
 { int year;
    cout << "Enter year greater than 2000: "<<endl;
    cin>>year;

    try{
if ( year<2000)
{
    throw "You entered a year less than 2000";

}
else{
    cout<< "Entered year is: "<<year<<endl;
}
    }

    catch ( const char*msg)

    { 
        cout << msg;
        
    }
 }
```
2)-


## OUTPUTS-
1)- <img width="336" alt="image" src="https://github.com/user-attachments/assets/0f3dfb57-de07-4894-bf4a-788d3f55c718">




