import java.util.Scanner;

public class QuadraticRoots {

    public static void main(String[]args){
        Scanner sc = new Scanner(System.in);

        System.out.println("Enetr values of a, b and c: ");
        double a = sc.nextDouble();
        double b = sc.nextDouble();
        double c = sc.nextDouble();

        double d= b*b-4*a*c;

      if(d>0){
        double r1 = (-b+Math.sqrt(d))/(2*a);
        double r2 = (-b-Math.sqrt(d))/(2*a);

        System.out.println("Roots are real and distinct:");
        System.out.println("Root 1: "+r1);
        System.out.println("Root 2: "+r2);
      }

      else if(d == 0){
        double r = -b / (2 * a);

        System.out.println("Roots are real and Eqaul: ");
        System.out.println("Roots = "+r);

      }else{
        System.out.println("Roots are Img...");
      }
      sc.close();
    }
    
}




