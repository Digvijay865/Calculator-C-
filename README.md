#include<iostream>
using namespace std;
int main() {
    int num1,num2,ans=0;
    char sign;
    cout<<"Enter the first Number :";
    cin>>num1;
    cout<<"Enter the Arithmatic Operator :";
    cin>>sign;
    cout<<"Enter the Second Number :";
    cin>>num2;
    switch(sign) {
        case '+':
         ans=num1+num2;
         break;
         case '-':
         ans=num1-num2;
         break;
         case '*':
         ans=num1*num2;
         break;
         case '/':
         ans=num1/num2;
         break;
         case '%':
         ans=num1%num2;
         break;
         default :
         cout<<"ERROR! invalid Operator or number entered"<<endl;
    }
    cout<<"The Answer is :-"<<ans<<endl;

}
