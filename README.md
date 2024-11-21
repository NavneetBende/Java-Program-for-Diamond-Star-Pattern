Printing Diamond Star Pattern
In this program we’re going to code diamond star pattern program .

In this program we’re taking input from user and store in the variable names as n and then we will run a for loop start from j=n to j>i+1 and then print spaces after that take a j from loop again start from j=0 to j<=i*2 after that print star statement and then again take another for loop start from i=n to i>0 and then take a for loop star from k=n to k– and then print spaces after that take another loop to print star

Java Program for Diamond Star Pattern
Algorithm:
Enter the number input from the user and store it in any variable.(‘n‘ in this case).
Run a loop ‘n’ number of times to iterate through each of the rows. From i=0 to i<n. The loop should be structured as for( i=0 ; i
Inside main loop take another loop start from j=n to  j– and then print System.out.println(“”);
After this inside main loop take another loop to print stars start from  j=0 to j++ and then print star System.out.println(“*”)
After 1st mail loop take another 2nd main loop start from i=n to i–
Inside this take 1st inner loop start from k=n to k– and then print spaces  System.out.print(” “);
After this take another inner loop to print stars start from j=0 to j++ System.out.print(“*”);
Code in Java:
import java.util.Scanner;
public class Pattern1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter No");
		int n=sc.nextInt();
		 for (int i=0; i<n; i++){ 
             for (int j=n; j>i+1; j--) 
               System.out.print(" "); 
             for (int j=0; j<=i*2; j++ ) 
               System.out.print("*"); 
          System.out.println(); 
      } 
		for(int i=n;i>0;i--)     
		   {
		      for(int k=n;k>i;k--)     
		         System.out.print(" ");    
		      for(int j=0;j<i*2-1;j++)     
		         System.out.print("*");    
		      System.out.println();     
		   }
	 }

}
