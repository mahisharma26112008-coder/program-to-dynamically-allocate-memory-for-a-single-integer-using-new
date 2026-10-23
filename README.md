# program-to-dynamically-allocate-memory-for-a-single-integer-using-new

#include<iostream>
  using namespace std;
 int main(){

int *p=new int;
cout<<"enter an intezar";
cin>>*p;

cout<<"value "<<*p;

delete p;

return 0; 
}
