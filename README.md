# ArraysToString 
Arrays
import java.util.Scanner;
public class ArraysToString {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Insert the number");
		Scanner in = new Scanner (System.in);
		int n= in.nextInt();
		int [] numbers = new int [n];
		for (int i = 0; i< numbers.length; i++) {
			numbers [i] = in.nextInt();
			if (numbers [i]%2==0)
				numbers [i]=0;
		}
		for (int i = 0; i<numbers.length; i++) {
			System.out.println(numbers [i] + "");
		}
		
	}

}

