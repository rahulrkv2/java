# java
package main;
import java.util.Scanner;
public class Evenodd {

	public static void main (String[] args)
		{
			System.out.println("enter a");
			Scanner input=new Scanner(System.in);
			int a=input.nextInt();
			if (a==2)
			{
				System.out.println("number is"+a);
			}
			else
			{
			if (a%2==0)
				
			{

				System.out.println("even");
			}

				else
			{

				System.out.println("odd");
			}
}
		}

}
