# // Lab_04_1.cpp
// < Tikhovsky Oleksiy  >
// Лабораторна робота № 4.1
// Цикли.
// Варіант 22                                                                                                                       #include <iostream>
#include <iostream>
#include <cmath>
using namespace std;
int main()
{ 
 int N, i;
 double S;
 cout << "N = "; cin >> N;
 cout << "i = "; cin >> i;
 S = 0;
 i = N;
 while (i <= 20)
 {
     S += (cos(i) + sin(i)) / (1 + cos(i) * sin(i));
     i++;
 }
 cout << S << endl;
S = 0;
 i = N;
 do {
 S += (cos(i) + sin(i)) / (1 + cos(i) * sin(i));
 i++;
 } while (i <= 20);
 cout << S << endl;
 S = 0;
 for (i=N; i <= 20; i++)
 {
 S += (cos(i) + sin(i)) / (1 + cos(i) * sin(i));
 }
 cout << S << endl;
 S = 0;
 for (i=20; i >= N; i--)
 {
 S += (cos(i) + sin(i)) / (1 + cos(i) * sin(i));
 }
 cout << S << endl;
 return 0;
}
