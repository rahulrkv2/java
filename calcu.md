# javaimport java.util.Scanner;
class For
	{ 
		public static void main (String[] args)
			{
				System.out.println("   CALCULATOR");
				System.out.println("----------------");
				System.out.println("   1.ADDITION");
				System.out.println("   2.SUBTRACTION");
				System.out.println("   3.MULTIPLICATION");
				System.out.println("   4.DIVISION");
				System.out.println("              ");
				System.out.println("ENTER YOUR CHOICE: ");
				Scanner input=new Scanner (System.in);
				int a=input.nextInt();
				int z;
				if(a==1)
					{ 
						System.out.println("enter X");
						int X=input.nextInt();
						System.out.println("enter Y");
						int Y=input.nextInt();
						z=X+Y;
						System.out.println("SUM :"+z);
					}
				if(a==2)
					{ 
						System.out.println("enter X");
						int X=input.nextInt();
						System.out.println("enter Y");
						int Y=input.nextInt();
						z=X-Y;
						System.out.println("DIFFERENCE :"+z);
					}

				if(a==3)
					{ 
						System.out.println("enter X");
						int X=input.nextInt();
						System.out.println("enter Y");
						int Y=input.nextInt();
						z=X*Y;
						System.out.println("PRODUCT :"+z);
					}


				if(a==4)
					{ 
						System.out.println("enter X");
						int X=input.nextInt();
						System.out.println("enter Y");
						int Y=input.nextInt();
						z=X/Y;
						System.out.println("QUOTIENT :"+z);
					}


			}		
	}
