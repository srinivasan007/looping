# looping
switch,while,do..while sample programs


//while

class whileex
{
public static void main(String args[])
{
int a=10;
	while(a<10)
	{
	System.out.println(a);
	a++;
	}
}
}



//do..while

class whileex
{
public static void main(String args[])
{
int a=10;
	do
	{
	System.out.println(a);
	a++;
	}while
}
}


//switch

import java.util.Scanner;
class switch1
{
public static void main(String args[])
{
int a=7,b=10;
Scanner s=new Scanner(System.in);
System.out.println("enter your choice:");
int op=s.nextInt();
switch(op)
{
case 1:
System.out.println("addition"+(a+b));
break;
case 2:
System.out.println("subtractio"+(a-b));
break;
case 3:
System.out.println("multification"+(a*b));
default:
System.out.println("invalid choice");
}
} 
}
