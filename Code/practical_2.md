public class OperatorsDemo {
    public static void main(String[] args) {

           int a = 10;
           int b = 20;

           // Arithmetic Operators

           System.out.println("Arithmetic Operators:................");
           System.out .println("a + b = " + (a + b));
           System.out .println("a - b = " + (a - b));
           System.out .println("a * b = " + (a * b));
           System.out .println("a / b = " + (a / b));
           System.out .println("a % b = " + (a % b));

           // Relational Operators
           System.out.println("Relational Operators:................");
           System.out.println("a==b:"+(a==b));
           System.out.println("a!=b: "+(a!=b));
           System.out.println("a>b: "+(a>b));
           System.out.println("a<b:"+(a<b));

           // Logical Operators
           System.out.println("Logical Operators:................");
           boolean x = true;
            boolean y = false;

            System.out.println("x && y: " + (x && y));
            System.out.println("x || y: " + (x || y));
            System.out.println("!x: " + (!x));


            //Bitwise Operators
            System.out.println("Bitwise Operators:................");
            System.out.println("a & b: " + (a & b));
            System.out.println("a | b: " + (a | b));
            System.out.println("a ^ b: " + (a ^ b));
            System.out.println("~a: " + (~a));
            System.out.println("a << 2: " + (a << 2));
            System.out.println("a >> 2: " + (a >> 2));

            // Assignment Operators
            System.out.println("Assignment Operators:................");
            int c= 30;
            c+=5;
            System.out.println("c+=5: " + c);

            c-=4;
            System.out.println("c-=4: " + c);

            c*=3;
            System.out.println("c*=3: " + c);

            c/=2;
            System.out.println("c/=2: " + c);

            //Unary Operators
            System.out.println("Unary Operators:................");
            int d = 5;
            System.out.println("d++: " + (d++));
            System.out.println("++d: " + (++d));
            System.out.println("d--: " + (d--));
            System.out.println("--d: " + (--d));


            // Ternary Operator
            System.out.println("Ternary Operator:................");
           System.out.println("Ternary Operator: " + (a > b ? "a is greater" : "b is greater"));
           System.out.println("Ternary Operator: " + (a < b ? "a is smaller" : "b is smaller"));
          

          }
}



