# javaimport java.util.Scanner;
class Leap
	{ 
		public static void main (String[] args)
			{
				System.out.println("enter year");
				Scanner input=new Scanner (System.in);
				int a=input.nextInt();
				if (a%4==0)
				{

					System.out.println("leap year");
				}

					else
				{

					System.out.println("not leap year");
				}
			}
		}
