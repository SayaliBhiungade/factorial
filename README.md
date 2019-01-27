# factorial
#include<iostream>
using namespace std; 
int main()    
{
 int num,factorial=1;
	//Ask for the number.
    cout<<"Enter a number to calculate it's factorial"<<endl;  
    cin>>num;
    for(int i=1;i<=num;i++)
    {
        factorial=factorial*i;
    }
    cout<<"Factorial of "<<num<<"="<<factorial<<endl;
    cin.get();
 
    return 0;
}
