# ex9 
package calcul;

import java.util.Scanner;

public class calculAB {

	public static void main(String[] args) {

		Scanner sc =new Scanner(System.in) ;
		System.out.println("donner n ");
		int n = sc.nextInt();
		int s=0; 
		int i=1;
		for (i=1;i<=n;i++)
			{if (n%2==0)
				System.out.println(i);
			s +=1;
			}
		System.out.println(s);
	
				
		}
}
