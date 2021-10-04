# c-Plus-Plus-Programs

Factorial program in C++

#include <iostream>  
using namespace std;  
int main()  
{  
   int i,fact=1,number;    
  cout<<"Enter any Number: ";    
 cin>>number;    
  for(i=1;i<=number;i++){    
      fact=fact*i;    
  }    
  cout<<"Factorial of " <<number<<" is: "<<fact<<endl;  
  return 0;  
}  
                                                      
 Armstrong Number in C++
                                                      
#include <iostream>  
using namespace std;  
int main()  
{  
int n,r,sum=0,temp;    
cout<<"Enter the Number=  ";    
cin>>n;    
temp=n;    
while(n>0)    
{    
r=n%10;    
sum=sum+(r*r*r);    
n=n/10;    
}    
if(temp==sum)    
cout<<"Armstrong Number."<<endl;    
else    
cout<<"Not Armstrong Number."<<endl;   
return 0;  
}     
