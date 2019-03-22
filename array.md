# javapackage main;
import java.util.Scanner;
public class Array
	{
	
		public static void main (String[] args)
		{
			System.out.println("enter size of array");
			Scanner input=new Scanner(System.in);
			int n=input.nextInt();
			int i,arr[]=new int[n];
			System.out.println("enter array elements");
			for (i=0;i<n;i++)
				{
					arr[i]=input.nextInt();
				
				}
			for (i=0;i<n;i++)
				{
				if (arr[i]%2==0)
					
				{

					System.out.println(arr[i]+" even");
				}

					else
				{

					System.out.println(arr[i]+" odd");
				}
			}
		
		}
	
	}
