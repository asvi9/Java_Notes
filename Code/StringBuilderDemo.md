public class StringBuilderDemo {

    public static void main(String[] args) {
    
        StringBuilder sb = new StringBuilder("Java");
        
        sb.append("Programming");
        System.out.println(sb);

        sb.insert(4,"SE");
        System.out.println(sb);

        sb.replace(5,7, "21");
        System.out.println(sb);

        sb.delete(4,8);
        System.out.println(sb);

        sb.reverse();
        System.out.println(sb);
    }
}
