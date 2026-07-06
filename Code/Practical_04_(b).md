import java.util.Scanner;

public class PrimeNumber {

    public static void main(String[] args){

        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        System.out.println("Enter a number: ");
        int i = 2;
        boolean isPrime = true;

        if(num<=1){
            isPrime = false;
        }else{
            do{
                if(num%i==0){
                    isPrime = false;
                    break;
                }
                i++;
            }while(i<=num/2);
        }
        if(isPrime){
            System.out.println(num + " is a prime number");
        }else{
            System.out.println(num + " is not a prime number");
        }
        sc.close();
    }   
    
}
