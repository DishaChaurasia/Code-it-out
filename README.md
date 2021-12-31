# Code-it-out
#include <iostream>

using namespace std;

int main() {
    int a[]={6,7,3,4,2};
    int b[5];
    for(int i=0;i<5;i++)
    {
       b[i]= a[5-i-1];
    }
    for(int i=0;i<5;i++)
    {
      cout<<b[i]<<" ";
    }
    
}
