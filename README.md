# NO-OF-DIGIT-PRESENT-IN-NUMBER
 IN THIS CODE WE ARE USING THE BASIC MATHS PORPERTIES 


#include <iostream>
using namespace std;


int main() {
   int i=0;
   int n;
   cout<<"whst is lyour name";
   cin>>n;
   while(n>0){
       int last=n%10;
       i=i+1;
       n=n/10;
       
   }cout<<i;

    return 0;
}
