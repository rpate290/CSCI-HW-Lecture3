# CSCI-HW-Lecture3
package part1;
import java.util.Scanner;
public class Hwpart3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("Enter number between 1 and 7 for day of the week: ");
		int number= input.nextInt();
		int num= number;
		String dayofWeek=("none");
		if (num==1){
			dayofWeek=("Sunday");}
		else if (num==2){
			dayofWeek=("Monday");}
		else if (num==3){
			dayofWeek=("Tuesday");}
		else if (num==4){
			dayofWeek=("Wed");}
		else if (num==5){
			dayofWeek=("Thursday");}
		else if (num==6){
			dayofWeek=("Friday");}
		else if (num==7){
			dayofWeek=("Saturday");}
		else {
			dayofWeek=("not a valid number");}
		System.out.println("The day of the week based on the number that you have entered is "+dayofWeek);
			
		}
		
	}



