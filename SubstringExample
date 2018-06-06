import java.util.*;
public class SubstringExample {
public static void main(String args[])
{
	Scanner s=new Scanner(System.in);
	System.out.println("enter the string");
	String g=s.next();
	ArrayList a1=new ArrayList();
	for(int i=0;i<g.length();i++)
	{
		for(int j=i+1;j<=g.length();j++)
		{
			a1.add(g.substring(i, j));
		}
	}
	Iterator i2=a1.iterator();
	while(i2.hasNext())
	{
		String g1=(String)i2.next();
		System.out.println(g1);
	}
	
}
}
