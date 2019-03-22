# javaimport java.util.Scanner;
class Swap 
	{ 
		public static void main (String[] args)
			{
				System.out.println("enter a");
				Scanner input=new Scanner (System.in);
				int a=input.nextInt();
				System.out.println("enter b");
				int b=input.nextInt();
				System.out.println("BEFORE SWAP");
				System.out.println("a=" +a);
				System.out.println("b=" +b);
				a=a+b;
				b=a-b;
				a=a-b;
				System.out.println("AFTER SWAP");
				System.out.println("a=:" +a);
				System.out.println("b=:" +b);
				}
	}
