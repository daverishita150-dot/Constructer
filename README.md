# Constructer

The different types of Constructers in Java

In OOPS in java there are Three different types of constructers namely:-
1) Non-Parameterised Constructers -> here no parameters are taken.
2) Parameterised Constructers ->they take parameters in them.
3) Copy Constructers ->They help to copy details of one object into another object.

Now here is the practical implementation of each :-
1) Non-parameterised Constructer
   class Student{
   string name,
   int age

   Student(){
   System.out.println("Constructer being called....");

2)Parametersied Constructer
class Student{
String name,
int age,

Student(String name,int age){
this.name=name;
this.age=age
}

//after creation of object
Student st1=new Student("radhika",23);

3)Copy Constructer
class Student{
String name,
int age

Student(Student st2){
this.name=st2.name;
this.age=st2.age

Student(){

}

//after creation of object
Student st1=new Student()
st1.name="rahul"
st1.age=22;

Student st2=new Student(st1)
