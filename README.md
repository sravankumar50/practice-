# practice-
#include<iostream>
using namespace std;

int main()
{
    int i,j;
    for(i=1;i<=7;i++,cout<<"\n") 
        for(j=1;j<=7;j++)
            (j<i)?cout<<" ": (cout<< j << " ");
    for(i=1;i<=6;i++,cout<<"\n")  
        for(j=7;j>=1;j--)    
         { 
           int k=8;
           (j>i+1)?cout<<" ":cout<< k-j << " ";     
            
         }
            
}
