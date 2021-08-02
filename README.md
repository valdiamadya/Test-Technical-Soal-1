// Test-Technical-Soal-1
#include <iostream>
#include <string>


using namespace std;
int main()
{
  double i, uang, to;
  
  cout << "uang bulan ini=";
  cin >> uang;
  i=1;
  while (i<=12)
  {
  
    uang = uang+(uang*0.025);
    to = uang;
    
    i=i+1;
  }
  
 cout << "uang bulan ini =" << to; 
 
}

//asas
