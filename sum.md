# javapackage main;
import java.util.Scanner;

public class Sum {

	public static void main (String[] args)
		{   int sum=0;
			System.out.println("enter a");
			Scanner input=new Scanner(System.in);
			int a=input.nextInt();
            for(int i=1;i<a;i++)
            {sum=sum+i;
}
            System.out.println("sum is : "+sum);
}
	}
