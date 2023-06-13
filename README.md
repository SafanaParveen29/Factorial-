# Factorial-

#include <iostream>
using namespace std;

int main()
{
    int n,temp=1;
    cout<<"Enter the number for to find the factorial:";
    cin>>n;
    cout<<"Factorial of "<<n<<":";
    for(int i=1;i<=n;i++){
        temp *= i; 
    }
    cout<<temp;

    return 0;
}
