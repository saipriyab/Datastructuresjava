import java.util.*;
public class StackExample {
    static int top=0;
    static int a[];
	public static void main(String args[])
	{
		Scanner s=new Scanner(System.in);
     System.out.println("how many elements of stack do you want to create");
     int n=s.nextInt();
     a=new int[n];
     System.out.println("please enter the option to performed the required option");
     System.out.println("1:push");
     System.out.println("2.pop");
     System.out.println("3:to know top element");
     System.out.println("4:display");
    int n1=s.nextInt();
    while(n1!=0)
    {
    switch(n1)
    {
    case 1:System.out.println("enter data");
           int p=s.nextInt(); 
    	   push(p);
           break;
    case 2:pop();
           break;
    case 3:knowtop();
    break;
    case 4:display();
            break;
    }
    n1=s.nextInt();
	}}
	public static void push(int p)
	{
		a[top]=p;
		top++;
		System.out.println("added");
	}
	public static void pop()
	{
		top--;
		a[top]=0;
		System.out.println("deleted");
	}
	public static void knowtop()
	{
		
		System.out.println(a[top-1]);
	}
	public static void display()
	{
		for(int p:a)
			System.out.println(p);
	}
}
