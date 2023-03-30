# C-
Organize your code snippets from Code with Harry and Apna College in this GitHub repository. It's a comprehensive learning resource for all programmers, where you can collaborate with others to gain new insights and build your skills effectively.

First Code 

// Online C++ compiler to run C++ program online
#include <iostream>

int main() {
    // Write C++ code here
    std::cout << "Hello world!";

    return 0;
}
  
  
Second Code 
    
#include<iostream>
using namespace std;

int main()
{
    int a = 14;
    int b = 15;
    
    cout<<"Here the value of a is "<<a<<" The Value of b is "<<b;
    
    return 0;
}    

    
3rd Code

#include<iostream>
using namespace std;

int main()
{
    int a = 14;
    int b = 15;
    float pi = 3.15;
    char ch = 'c';
    
    cout<<"\nHere the value of a is "<<a<<" \nThe Value of b is "<<b;
    cout<<"\nThe value of pie is "<<pi;
    cout<<"\nThe value of char is "<<ch;
    return 0;
}    

4th Code

#include<iostream>
using namespace std;

int main()
{
    int num1, num2;
    cout<<"Enter the value of num1:\n"; /* '<<' is called Insertion operator */
    cin>>num1; /* is called Extraction operator */
    
    cout<<"Enter the value of num2:\n"; /* '<<' is called Insertion operator */
    cin>>num2; /* is called Extraction operator */
    
    cout<<"The sum is "<< num1+num2;
    
    return 0;
}    

5th Code 

// There are two types of header files:
// 1. System header files: It comes with the compiler 
#include<iostream>
// 2. User defined header files: It is written by the programmer
// #include "this.h" --> This will produce an error if this.h is no present in the current directory 

using namespace std;

int main()
{
    int a=4, b=5;
    cout<<"Operators in C++:"<<endl;
    cout<<"Following are the types of operators in C++"<<endl;
    
    // Arthmetic operators
    cout<<"The value of a + b is " <<a+b<<endl;
    cout<<"The value of a - b is " <<a-b<<endl;
    cout<<"The value of a * b is " <<a*b<<endl;
    cout<<"The value of a / b is " <<a/b<<endl;
    cout<<"The value of a % b is " <<a%b<<endl;
    cout<<"The value of a++ is " <<a++<<endl;
    cout<<"The value of a-- is " <<a--<<endl;
    cout<<"The value of ++a is " <<++a<<endl;
    cout<<"The value of --a is " <<--a<<endl;
    cout<<endl;
    cout<<endl;
    
    // Assignment Operators --> used to assign values to variables 
    // int a = 3, b = 9;
    // char d = 'd';
    
    // Comparison operators
    cout<<"Following are the comparison operators in c++"<<endl;
    cout<<"The value of a == b is "<<(a==b)<<endl;
    cout<<"The value of a != b is "<<(a!=b)<<endl;
    cout<<"The value of a >= b is "<<(a>=b)<<endl;
    cout<<"The value of a <= b is "<<(a<=b)<<endl;
    cout<<"The value of a > b is "<<(a>b)<<endl;
    cout<<"The value of a < b is "<<(a<b)<<endl;
    
    // Logical operators
    cout<<"Following are the logical operators in c++"<<endl;
    cout<<"The value of this logical and operator ((a==b) && (a<b) is:" <<((a==b) && (a<b))<<endl;
    cout<<"The value of this logical or operator ((a==b) || (a<b) is:" <<((a==b) || (a<b))<<endl;
    cout<<"The value of this logical not operator (!(a==b) is:" <<(!(a==b))<<endl;
    
    return 0;
}    
