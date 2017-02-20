Q1) Can you overload a method with same return type.? Explain your answer with proper logic.
yes we can overload a method with same return type


import java.util.Scanner;
public class Main {
public static void main(String args[])
{
	Scanner s=new Scanner(System.in);
System.out.println("1.Sum of two numbers \n2.Sum of three numbers");  
int i =s.nextInt();
if(i==1){
System.out.println("Enter two numbers");
int x=s.nextInt();
int y=s.nextInt();
sum(x,y);  //calling the method sum which accepts two integers
}
if(i==2){ System.out.println("Enter three numbers");
int b=s.nextInt();
int c=s.nextInt();
int d=s.nextInt();

int r=sum(b,c,d);  //calling the method sum which accepts three integers
}

}
public static int sum(int a,int b)  //creating a method sum which accepts two integers
{
	return (a+b);
}
public static int sum(int a,int b,int c) //creating a method sum which accepts three integers
{
	return (a+b+c);
}
}

Q2) Write a program in java using Arrays, that sorts the element in descending order. java.util.Scanner;
public class acad { public static void main(String args[]){
Scanner s=new Scanner(System.in); 
System.out.println("Enter the number of elements in array ");
int n=s.nextInt(); //getting the size of the array 
System.out.println("Enter the elements in array"); 
int[] a=new int[n]; //defining an integer array of size n 
for(int i=0;i=0;i--) //loop which is used to print it in a reverse order
{ 
System.out.println(a[i]); 
}
}
}
