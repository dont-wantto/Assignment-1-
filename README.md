# Assignment-1-
Assignment -1 on cpp by  Nuren Nafisa mam. 
____________________________________________________________________________________

Problem 1: Circle Class
Create a class called "Circle" that represents a circle. The class should have member variables
for the radius and member functions to set the radius, calculate the area, and display the circle's
details.
solving:
#include<bits/stdc++.h>
using namespace std;
class circle{
double radius;
public:
    void setdata(double r){
        radius=r;

    }
    double getdata(){
        return 3.1416*radius*radius;
    }
};
int main()
{ circle c;
    double rad;
    cout<<"enter radius= ";
    cin>>rad;
    c.setdata(rad);
    cout<<"the radius of the circle is ="<<rad<<endl;
    cout<<"the area of the circle is="<<c.getdata();
return 0;
}
__________________________________________________________________________________________________________________________________________________________________________________________
Problem 2: Person Class
Create a class called "Person" that represents a person. The class should have
member variables for the person's name and age, and member functions to set the
name, set the age, and display the person's details.
solving:
#include<bits/stdc++.h>
using namespace std;
class person{
 int age ;
 string name;
public:
    void setdata(int a, string n){
        age=a;
        name=n;}
    void   show(){
  cout<<"the person's age is="<<age<<endl;
cout<<"the persons's name is ="<<name<<endl;
}};
int main()
{ person p;
    int  age;
    string n;
    cout<<"enter age:";
    cin>>age;
     cout<<"enter name:";
    cin>>n;
p.setdata(age,n);
p.show();
    return 0;
}
___________________________________________________________________________________________________________________________________________________________________________________________
Problem 3: Student Information System
Create a class called "Student" that represents a student. The class should have private
member variables for the student's name and ID. Implement member functions to set
and get the student's name and ID. Finally, create an object of the "Student" class and
demonstrate the use of the member functions.
solving:
#include<bits/stdc++.h>
using namespace std;
class student{
 int id ;
 string name;
public:
    void setdata(int a, string n){
        id=a;
        name=n;}
    int getid(){
        return id;
}
string getname(){
    return name;
}};
int main()
{ student  p;
    int  id;
    string n;
       cout<<"enter name:";
     getline (cin,n);
    cout<<"enter id:";
    cin>>id;
p.setdata(id,n);
cout<<"the id of the student is = "<<p.getid()<<endl;
cout<<"the name of the student is = "<<p.getname()<<endl;
    return 0;
}
___________________________________________________________________________________________________________________________________________________________________________________________
Problem 4: Rectangle Class
Create a class called "Rectangle" that represents a rectangle. The class should have
private member variables for the length and width. Implement member functions to set
the length and width, calculate the area and perimeter, and display the rectangle's
details. Finally, create an object of the "Rectangle" class and demonstrate the use of the
member functions.
solving:
#include<bits/stdc++.h>
using namespace std;
class  rectangle{
double length, width;
public:
    void setdata(double l, double w){
       length = l;
       width=w;
       
       }
   double  getlength(){
        return length;
}
double getwidth(){
    return width;
}
double calculatearea(){

    return length*width;
}
double calculateperi(){
    return 2*(length+width);
}
void  show(){
cout<<"the length of the rectangle is = "<<getlength()<<endl;
cout<<"the width of the rectangle is = "<<getwidth()<<endl;
cout<<"the area of the rectangle is = "<<calculatearea()<<endl;
cout<<"the perimeter of the rectangle is = "<<calculateperi()<<endl;
}


};
int main()
{ rectangle r;
double length,width;
cout<<"enter length =";
cin>>length;
cout<<"enter width = ";
cin>>width;
r.setdata(length,width);
 r.show();


    return 0;
}


                       ..........................end brooo.......


















































