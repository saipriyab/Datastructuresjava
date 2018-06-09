import java.util.*;
public class StringPermutationsexample {
public static void main(String args[])
{
String a="abc";
		System.out.println();
	char a1[]=a.toCharArray();
	Perm(a1,0,a.length());
	}

private static void Perm(char a[], int k, int length) {
   if(k==length)
   {
	   String j1="";
	   for(int j=0;j<length;j++)
	   {
		  System.out.print(a[j]);
	   }
		   System.out.println();
   }
   else
   {
	   for(int i1=k;i1<length;i1++)
	   {
	   char temp=0;
	   temp=a[k];
	   a[k]=a[i1];
	   a[i1]=temp;
	   Perm(a,k+1,length);
	   temp=a[k];
	   a[k]=a[i1];
	   a[i1]=temp;
	   }
   }
}


}
