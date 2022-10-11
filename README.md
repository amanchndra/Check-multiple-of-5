# Check-multiple-of-5
Check if N(number) is multiple of 5 or not.
package lecture;

import java.util.Scanner;

public class nnnn {
	public static void main(String[] args) {
		System.out.println("multiple of 5 is");

		Scanner scn = new Scanner(System.in);
		int n = scn.nextInt();
		int rem = n % 5;
		if (rem == 0) {
			System.out.println("Yes this is multiple of 5");
		} else if (rem == 1) {
			System.out.println("not a multiple");
		} else {
			System.out.println("Yeh nahi hoga bruh, TRY AGAIN !!!");
		}

	}

}
