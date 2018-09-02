# a3_10684120.cc
c++program that accepts a score and outputs the grade
//Program to tell the grade of a score when entered in it
#include<iostream>
using namespace std;

int main()
{
int score;
cout<<"Student score:";
cin>>score;
if(score>=80)
{
cout<<"score:"<<score<<endl;
cout<<"Grade:A";
}
else if(score>=75)
{
 cout<<"score:"<<score<<endl;
 cout<<"Grade:B+";
}
else if(score>=70)
{
cout<<"score:"<<score<<endl;
cout<<"Grade:B";
}
else if(score>=65)
{
cout<<"score:"<<score<<endl;
cout<<"Grade:c+";
}
else if(score>=60)
{
 cout<<"score:"<<score<<endl;
 cout<<"Grade:c";
}
else if(score>=55)
{
cout<<"score:"<<score<<endl;
cout<<"Grade:D+";
}
else if(score>=50)
{
cout<<"score:"<<score<<endl;
cout<<"Grade:D";
}
else if(score>=45)
{
 cout<<"score:"<<score<<endl;
 cout<<"Grade:E";
}
else if(score<=44)
{
cout<<"score:"<<score<<endl;
cout<<"Grade:F";
}
return 0;
}
