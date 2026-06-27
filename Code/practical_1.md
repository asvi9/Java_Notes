
public class HelloWorldDemo {

    public static void main(String[] args) {

        // Display Hello World
        System.out.println("Hello World");

        // Variables and Data Types
        int age = 25;
        float percentage = 85.5f;
        char grade = 'A';
        boolean passed = true;
        double salary = 45000.75;

        // Display variable values
        System.out.println("Age = " + age);
        System.out.println("Percentage = " + percentage);
        System.out.println("Grade = " + grade);
        System.out.println("Passed = " + passed);
        System.out.println("Salary = " + salary);

        // Implicit Type Casting (Widening)
        int num = 100;
        double d = num; // int to double

        System.out.println("Integer Value = " + num);
        System.out.println("Converted to Double = " + d);

        // Explicit Type Casting (Narrowing)
        double price = 99.99;
        int p = (int) price; // double to int

        System.out.println("Original Double Value = " + price);
        System.out.println("Converted Integer Value = " + p);
    }
}
