# c-program-
c program  for students details read and print
#include<stdio.h>
#include<conio.h>
#define p printf
#define s scanf
struct student
{
int age;
char name [20];
int rollno;	
};

int main()
{
	struct student s1;
	p("Enter the student details here-->\n ");
	p("----------------------------------\n");
	p("Enter the student name :\n ");
	s("%s",&s1.name);
	p("Enter the student rollno :\n ");
	s("%d",&s1.rollno);
	p("Enter the student age :\n ");
	s("%d",&s1.age);
	p("----------------------------------\n");
	p("The given record of student is \n");
	p("As follows\n");
	p("--> Student name:%s\n",s1.name);
	p("--> Student rollno:%d\n",s1.rollno);
	p("--> Student age:%d\n",s1.age);
	return 0;
}
