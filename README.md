# simple-calculator1
#Codsoft
#include<iostream>
using namespace std;
int main(){
int x,y;
cout<<"Enter the first number ";

cin>>x;
cout<<"Enter the second number ";
cin>>y;
char operation;
cout<<"Enter the operation which you will perform ";
cin>>operation;
switch(operation){
case '+':
cout<<"the answer is "<<x+y<<endl;
break;
case '-':
cout<<"the answer is "<<x-y<<endl;
break;
case '*':
cout<<"the answer is "<<x*y<<endl;
break;
case '/':
cout<<"the answer is "<<float(x/y)<<endl;
break;
case '%':
cout<<"the answer is "<<x%y<<endl;
break;
}


    return 0;
}
