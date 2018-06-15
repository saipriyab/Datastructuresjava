import java.util.*;
public class Game {
public static void main(String args[])
{
	System.out.println("enter");
	Scanner s=new Scanner(System.in);
	int t=s.nextInt();
	for(int i=0;i<t;i++)
	{
		int n=s.nextInt();
		int a[]=new int[n];
		for(int j=0;j<n;j++)
			a[j]=s.nextInt();
		ArrayList a2=new ArrayList();
		for(int k=0;k<n;k++)
			a2.add(s.nextInt());
		int count=0;
		for(int k2=0;k2<a.length;k2++)
		{
			int p6=a[k2];
			for(int p7=0;p7<a2.size();p7++)
			{
				if((Integer)a2.get(p7)<p6)
				{
					count++;
					a2.remove(p7);
				}
			}
		}
		System.out.println(count);
	}
}
}
