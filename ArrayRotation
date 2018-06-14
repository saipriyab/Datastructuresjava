import java.util.*;
public class StringAllSubstringsExample {
public static void main(String args[])
{
	int ar[]= {1,2,3,4,5,6,7};
	System.out.println("eneter");
	Scanner s=new Scanner(System.in);
	int p=s.nextInt();
	int b[]=new int[p];
	int k=0;
	for(int p2=0;p2<p;p2++,k++)
		b[p2]=ar[k];
	int l=ar.length-p;
	for(int p3=0;p3<=l-1;p3++)
	{
		ar[p3]=ar[p];
		p++;
	}
	for(int p4=l,p6=0;p4<ar.length;p4++)
	{
		ar[p4]=b[p6];
		p6++;
	}
for(int l1:ar)
	System.out.print(l1+" ");
}
}
