- #include <iostream>
using namespace std;
int main() 
/*
//INTEGER 5. 
. Даны целые положительные числа A и B (A > B). На отрезке длины A
размещено максимально возможное количество отрезков длины B (без
наложений). Используя операцию взятия остатка от деления нацело, найти
длину незанятой части отрезка A*/
/*{
double A; 
double B;
int C;
double d;
cout << "naiti ostatok ";
cin >> A >> B ;
C = A / B;
d = A - ( C * B);
cout << C << endl;
cout << d << endl;
return 0;
}*/
/*INTEGER 6 Дано двузначное число. Вывести вначале его левую цифру (десятки), а затем — его правую цифру (единицы). Для нахождения десятков
использовать операцию деления нацело, для нахождения единиц — операцию взятия остатка от деления.*/
/*{
int a;
int d;
int e;
cout << "naiti decatki i edinici ";
cin >> a;
d = a/10;
e = a - (d * 10);
cout << d << endl;
cout << e << endl;
return 0;
}*/
//INTEGER 7 . Дано двузначное число. Найти сумму и произведение его цифр.
/*{
  int A;
int e;
int d;
int P;
int S;
cout << "summu i proizvedenie ";
cin >> A ;
d = A/10;
e = A - (d*10);
S = d + e;
P = d * e;
cout << P << endl;
cout << S << endl;
return 0;
}*/
//INTEGER 8  Дано двузначное число. Вывести число, полученное при перестановке цифр исходного числа.
/*{
int A;
int e;
int d;
int G;
cout << "vtoroe chislo "; 
cin >> A;
d = A/10;
e = A - (d*10);
G = e*10 + d;
cout << G << endl;
return 0;
}*/ 
//INTEGER 9 Дано трехзначное число. Используя одну операцию деления нацело,
//вывести первую цифру данного числа (сотни).
{
 /*{int A;
  int S;
  cout << "naiti sotni ";
  cin >> A;
  S = A/100;
  cout << S << endl;
  return 0;
}*/
//INTEGER 10 Дано трехзначное число. Вывести вначале его последнюю цифру
//(единицы), а затем — его среднюю цифру (десятки).
/*{
 int A;
 int s;
 int b;
 int e;
 int d;
 cout << "naiti edinici i destki ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
cout << e << endl;
cout << d << endl;
return 0;
}*/
//INTEGER 11  Дано трехзначное число. Найти сумму и произведение его цифр
{
/*{
  int A;
 int s;
 int b;
 int e;
 int d;
 int S;
 int P;
 cout << "naiti summu i proizvedenie ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
P = s * d * e;
S = s + d + e;
cout << S << endl;
cout << P << endl;
return 0;  
}*/
//INTEGER 12 Дано трехзначное число. Вывести число, полученное при прочтении исходного числа справа налево.
/*{
 int A;
 int s;
 int b;
 int e;
 int d;
 int V;
 cout << "naiti chislo sprava nalevo ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
V = e * 100 + d * 10 + s;
cout << V << endl;
return 0;  
}*/
//INTEGER 13 Дано трехзначное число. В нем зачеркнули первую слева цифру и
//приписали ее справа. Вывести полученное число. 
/*{
int A;
 int s;
 int b;
 int e;
 int d;
 int V;
 cout << "naiti chislo ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
V = d * 100 + e * 10 + s;
cout << V << endl;
return 0;  
}*/
//INTEGER 14  Дано трехзначное число. В нем зачеркнули первую справа цифру
//и приписали ее слева. Вывести полученное число.
/*{
int A;
 int s;
 int b;
 int e;
 int d;
 int V;
 cout << "naiti chislo ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
V = e * 100 + s * 10 + d;
cout << V << endl;
return 0;  
}*/
//INTEGER 15 . Дано трехзначное число. Вывести число, полученное при перестановке цифр сотен и десятков исходного числа (например, 123 перейдет в
//213).
/*{
int A;
 int s;
 int b;
 int e;
 int d;
 int V;
 cout << "naiti chislo ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
V = d * 100 + s * 10 + e;
cout << V << endl;
return 0;  
}*/
//INTEGER 16 Дано трехзначное число. Вывести число, полученное при перестановке цифр десятков и единиц исходного числа (например, 123 перейдет
//в 132).
/*{
int A;
 int s;
 int b;
 int e;
 int d;
 int V;
 cout << "naiti chislo ";
 cin >> A;
s = A/100;
b = A - (s * 100);
d = b/10;
e = b - d * 10;
V = s * 100 + e * 10 + d;
cout << V << endl;
return 0;  
}
*/
