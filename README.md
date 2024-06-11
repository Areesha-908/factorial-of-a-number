# factorial of a number
  a program to find the factorial of a number
#include<iostream>
using namespace std;
int main()
{
int i=1,num,f=1;
cout<<"enter a number"<<endl;
cin>>num;
while(i<=num)
{
f=f*i;
i++;
}
cout<<"factorail of "<< num <<" is =" << f <<endl;
return 0;
}
