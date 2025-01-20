# First-n-numbers
First n Numbers

import java.util.Scanner;

public class FirstNNumbers {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the value of n: ");
        int n = sc.nextInt();
        System.out.println("First " + n + " numbers:");
        for (int i = 1; i <= n; i++) {
            System.out.print(i + " ");
        }
    }
}

Output

Enter the value of n: 5  
First 5 numbers:  
1 2 3 4 5
