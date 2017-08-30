//start
#include<iostream>
using namespace std;
int main()  {
  int a,b;
  cout<<"Enter two no."<<endl;
  cin>>a>>b;
  try {
    if(b!=0)  {
      cout<<"Division : "<<(a/b)<<endl;
    }
    else  
      throw b;
  }
  catch(int b)  {
    cout<<"Division is not possible"<<endl;
  }
}
