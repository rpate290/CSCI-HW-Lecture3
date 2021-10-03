# CSCI-HW-
package part1;
import java.util.Scanner;
public class Hwpart2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("Enter an Integer ");
		int number1= input.nextInt();
		Scanner input2= new Scanner(System.in);
		System.out.print("Enter another Integer ");
		int number2= input2.nextInt();
		Scanner input3= new Scanner(System.in);
		System.out.print("Enter a Final Integer ");
		int number3= input3.nextInt();
		int x= number1;
		int y= number2;
		int z=number3;
		int highNumber= greatestnumFunction(x,y,z);
		System.out.println("The greatest of the numbers that you have entered is "+highNumber);  
		
	}

	public static int greatestnumFunction(int x, int y, int z) {
		int great = 0;
			if (x>y) and (x>z); {
				great = x;}
			 if (y>x) and (y>z); {
				 great = y;}
			if (z>x) and (z>y);{
				 great = z;}
			return great;
			}

	private static void and(boolean b) {
		// TODO Auto-generated method stub
		
	}
				
				
			
					
				
	
	}		 
	
