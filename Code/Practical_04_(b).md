import java.util.Scanner;

public class PrimeNumber {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a Number: ");
        int num = sc.nextInt();

        int i = 2;
        boolean isPrime = true;
        
        if (num <= 1) {
            isPrime = false;
        } else if (num == 2) {
            isPrime = true; 
        } else {
            do {
                if (num % i == 0) {
                    isPrime = false;
                    break;
                }
                i++;
            } while (i <= num / 2);
        }

        if (isPrime) {
            System.out.println(num + " is a Prime Number");
        } else {
            System.out.println(num + " is Not a Prime Number");
        }
        
        sc.close();
    }
}
