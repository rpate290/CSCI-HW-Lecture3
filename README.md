# CSCI-HW-Lecture3
package part1;
import java.util.Scanner;
public class Hwpart1 {


	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input= new Scanner(System.in);
		System.out.print("Enter an integer: ");
		int x= input.nextInt();
		int c= checkFunction(x);
		if (c==1)
		System.out.println("The number that you entered is a positive number");
		else if (c==0)
		System.out.println("The number that you entered is a negative number");
		else if (c==2)
			System.out.println("The number that you have entered is zero, neither positive nor negative");
	}
	public static int checkFunction(int x) {
		if (x>0)
			return 1;
		else if (x==0)
			return 2;
		else
			return 0;
	}
}
