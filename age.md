# javaimport java.util.Scanner;
class Age
	{ 
		public static void main (String[] args)
			{   int yr,mn,ds;
				System.out.println("enter date, month and year of birth");
				Scanner input=new Scanner (System.in);
				int a=input.nextInt();
				int b=input.nextInt();
				int c=input.nextInt();
	            System.out.println("AGE ON 31-12-2018 :");
	            ds=31-a;
	            mn=12-b;
	            yr=2018-c;
			    System.out.println(+ds+" days "+mn+" months "+yr+"years old");
			}
	}
