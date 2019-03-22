# javaimport java.util.Scanner;
class Display 
	{ 
		public static void main (String[] args)
			{
				System.out.println("enter a number");
				Scanner input=new Scanner (System.in);
				int d=input.nextInt();
				System.out.println("you have entered:" +d);
			}
	}
