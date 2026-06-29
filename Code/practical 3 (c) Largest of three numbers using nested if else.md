import java.util.Scanner;

public class LargestOfThree {
    
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("Enter three Numbers: ");
        int a = sc.nextInt();
        int b = sc.nextInt();
        int c = sc.nextInt();

        if(a>b){
            if(a>c){
                System.out.println("Largerst Number = "+ a);
            }else{
                System.out.println("Largest Number ="+c);
            }
         } else{
                if(b>c){
                    System.out.println("Largest Number = "+b);
                }else{
                    System.out.println("Largest Number ="+c);
                }
            }
        sc.close();

    }
}
