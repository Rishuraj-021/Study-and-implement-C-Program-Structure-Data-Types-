# Experiment-2
Aim:To study and implement C++ Program Structure (Data Types)

Theory: A C++ program follows a basic structure that includes:
Header files (#include <iostream>) for input/output
Main function (int main()) where execution starts
Statements inside the main block
Return statement to end the program
C++ supports different data types to store different kinds of values:

Data Type	Example	Purpose
int	10	For whole numbers
float	3.14	For decimal numbers
char	'A'	For single characters
bool	true	For true/false values
string	"Hello"	For text *(needs <string>)
These are used to declare variables that store input, perform calculations, and display output.

Code:#include<iostream>
#include<string>
using namespace std;
int main()
{
    int a;
    cout<<"Enter any Integer"<<endl;
    cin>>a;
    char b;
    cout<<"Enter a character"<<endl;
    cin>>b;
    float c;
    cout<<"Enter a number"<<endl;
    cin>>c;
    string d;
    cout<<"Enter a word"<<endl;
    cin>>d;
    double e;
    cout<<"Enter a big number"<<endl;
    cin>>e;
    bool f;
    cout<<"Enter 1 or 0"<<endl;
    cin>>f;
    cout<<"Float= "<<c<< " and the size is "<<sizeof(c)<<" bytes"<<endl;
    cout<<"Integer= "<<a<< " and the size is "<<sizeof(a)<<" bytes"<<endl;
    cout<<"Character= "<<b<< " and the size is "<<sizeof(b)<<" bytes"<<endl;
    cout<<"Double= "<<e<< " and the size is "<<sizeof(e)<<" bytes"<<endl;
    cout<<"String= "<<d<< " and the size is "<<sizeof(d)<<" bytes"<<endl;
    cout<<"Boolean= "<<f<< " and the size is "<<sizeof(f)<<" bytes"<<endl;
}    

Output: PS C:\Users\Rishu Raj\New folder\c programme> cd "c:\Users\Rishu Raj\New folder\c programme\" ; if ($?) { g++ a.cpp -o a } ; if ($?) { .\a }
Enter any Integer
5
Enter a character
bh
Enter a number
Enter a word
Enter a big number
Enter 1 or 0
Float= 0 and the size is 4 bytes
Integer= 5 and the size is 4 bytes
Character= b and the size is 1 bytes
Double= 8.0082e-307 and the size is 8 bytes
String=  and the size is 24 bytes
Boolean= 0 and the size is 1 bytes
