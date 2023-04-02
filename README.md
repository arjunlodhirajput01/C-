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

6th Code

#include<iostream>
using namespace std;

int c = 45;

int main()
{
    int a, b, c;
    cout<<"Enter the value of a:"<<endl;
    cin>>a;
    cout<<"Enter the value of b:"<<endl;
    cin>>b;
    c = a+b;
    cout<<"The sum of a + b is "<<c<<endl;
    cout<<"The Global c is "<<::c;
    
    return 0;
}

7th Code 

#include<iostream>
using namespace std;

int c = 45;

int main()
{
    // int a, b, c;
    // cout<<"Enter the value of a:"<<endl;
    // cin>>a;
    // cout<<"Enter the value of b:"<<endl;
    // cin>>b;
    // c = a+b;
    // cout<<"The sum of a + b is "<<c<<endl;
    // cout<<"The Global c is "<<::c;
    
    float d = 34.4f;
    long double e = 34.4L;
    
    cout<<"The size of 34.4 is "<<sizeof(34.4f)<<endl;
    cout<<"The size of 34.4 is "<<sizeof(34.4F)<<endl;
    cout<<"The size of 34.4 is "<<sizeof(34.4l)<<endl;
    cout<<"The size of 34.4 is "<<sizeof(34.4L)<<endl;
    return 0;
}

8th Code
    
#include<iostream>
using namespace std;

// int c = 45;

int main()
{
    // *********************Built in Data Types *****************
    // int a, b, c;
    // cout<<"Enter the value of a:"<<endl;
    // cin>>a;
    // cout<<"Enter the value of b:"<<endl;
    // cin>>b;
    // c = a+b;
    // cout<<"The sum of a + b is "<<c<<endl;
    // cout<<"The Global c is "<<::c;
    
    // / ********************* float, double, long double Literals *****************
    
    // float d = 34.4f;
    // long double e = 34.4L;
    
    // cout<<"The size of 34.4 is "<<sizeof(34.4f)<<endl;
    // cout<<"The size of 34.4 is "<<sizeof(34.4F)<<endl;
    // cout<<"The size of 34.4 is "<<sizeof(34.4l)<<endl;
    // cout<<"The size of 34.4 is "<<sizeof(34.4L)<<endl;
    
        // / ********************* Reference Variables *****************
        // Rohan Das ----> Monty ------> Rohu ------> Dangerous Coder
        
        // float x = 455;
        // float & y = x;
        // cout<<x<<endl;
        // cout<<y<<endl;
        
         // / ********************* Typecasting *****************
         
         int a = 45;
         int b = 45.5;
         
         cout<<"The value of a is "<<(float)a<<endl;
         cout<<"The value of a is "<<float(a)<<endl;
         
         cout<<"The value of b is "<<(int)b<<endl;
         cout<<"The value of b is "<<int(b)<<endl;
         int c = int(b);
         
         cout<<"The expression is "<<a + b<<endl;
         cout<<"The expression is "<<a + int(b)<<endl;
         cout<<"The expression is "<<a + (int)b<<endl;
         
    return 0;
}    

9th Code 

#include<iostream>
#include<iomanip>
using namespace std;

int main()
{
    // int a = 34;
    // cout<<+"The value of a was:"<<a;
    // a = 45;
    // cout<<"The value of a is:"<<a;
    
    // Constants in C++
    
    // const int a = 3;
    // cout<<"The value of a was: "<<a<<endl;
    // a = 45; // You Will get an error because a is a constant
    // cout<<"The value of a is: "<<a<<endl;
    
    // Manipulators in c++
    // int a = 1, b = 12, c = 123;
    
    // cout<<"The value of a without setw is "<<a<<endl;
    // cout<<"The value of a without setw is "<<b<<endl;
    // cout<<"The value of a without setw is "<<c<<endl;
    
    // cout<<"The value of a with setw is "<<setw(4)<<a<<endl;
    // cout<<"The value of b with setw is "<<setw(4)<<b<<endl;
    // cout<<"The value of c with setw is "<<setw(4)<<c<<endl;
    
    // Operator Precedence
    int a = 3, b = 4;
    // int c = (4*5)+b;
    int c = ((((a*5)+b)-45)+87);
    cout<<c;
    return 0;
}

10th Code
    
#include<iostream>
using namespace std;

int main()
{
    int age;
    cout<<"Tell me your age :"<<endl;
    cin>>age;
    
    // // Selection control sturture if-else ladder
    
    // if(age<18)
    // cout<<"You are not allowed to enter in party"<<endl;
    // else if(age==18)
    // cout<<"You are still not allowed to enter in party"<<endl;
    // else{
    //     cout<<"You are allowed to enter in party"<<endl;
    // }
    
    // Selection control structure: Switch Case statements
    
    switch(age)
    {
        case 18:
        cout<<"You are You are 18"<<endl;
        break;
        
        case 21:
        cout<<"You are You are 21"<<endl;
        break;
        
        case 28:
        cout<<"You are You are 28"<<endl;
        break;
        
        defult:
        cout<<"No special cases"<<endl;
        break;
    }
    
    return 0;
}

                                       
Code 11;
                                       
#include <iostream>

using namespace std;
int main()
{
    /*Loops in C++:
    There are three types of loops in C++:
        1. For loop
        2. While Loop
        3. do-While Loop
    */

    /*For loop in C++*/
    // int i=1;
    // cout<<i;
    // i++;

    // Syntax for for loop
    // for(initialization; condition; updation)
    // {
    //     loop body(C++ code);
    // }

    // for (int i = 1; i <= 40; i++)
    // {
    //     /* code */
    //     cout<<i<<endl;
    // }

    // Example of infinite for loop
    // for (int i = 1; 34 <= 40; i++)
    // {
    //     /* code */
    //     cout<<i<<endl;
    // }

    /*While loop in C++*/
    // Syntax:
    // while(condition)
    // {
    //     C++ statements;
    // }

    //  Printing 1 to 40 using while loop
    // int i=1;
    // while(i<=40){
    //     cout<<i<<endl;
    //     i++;
    // }

    // Example of infinite while loop
    // int i = 1;
    // while (true)
    // {
    //     cout << i << endl;
    //     i++;
    // }

    /* do While loop in C++*/
        // Syntax:
        // do
        // {
        //     C++ statements;
        // }while(condition);
        
    //  Printing 1 to 40 using while loop
    // int i=1;
    // do{
    //     cout<<i<<endl;
    //     i++;
    // }while(false);

    return 0;
}


Code 11

#include<iostream>
using namespace std;

int main()
{
    for (int i = 0; i < 8; i++)
    {
        // code
        
        if(i == 2){
        continue;
        }
        cout<<i<<endl;
    }
    return 0;
}

Code 12

#include<iostream>
using namespace std;

int main(){
    // What is a pointer? ----> Data type which holds the address of other data types
    int a=3;
    int* b;
    b = &a;

    // & ---> (Address of) Operator
    cout<<"The address of a is "<<&a<<endl;
    cout<<"The address of a is "<<b<<endl;

    // * ---> (value at) Dereference operator
    cout<<"The value at address b is "<<*b<<endl;

    // Pointer to pointer
    int** c = &b;
    cout<<"The address of b is "<<&b<<endl;
    cout<<"The address of b is "<<c<<endl; 
    cout<<"The value at address c is "<<*c<<endl; 
    cout<<"The value at address value_at(value_at(c)) is "<<**c<<endl; 

    return 0;
}
