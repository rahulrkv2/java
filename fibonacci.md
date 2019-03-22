# javapackage main;

import java.util.Scanner;

public class Fib {

	public static void main (String[] args)
		{
			System.out.println("enter a");
			Scanner input=new Scanner(System.in);
			int a=input.nextInt();
			int x=0,y=1;	
			while(a!=0)
			{ 
				System.out.print("  "+x);	
				int temp=x;
				x=y;
				y=temp+y;
				a=a-1;
			}
		}
}
