public class Main {
    public static void main(String[] args) {
        
        double num1 = 10;
        double num2 = 5;
        char operator = '+'; // Choose a type of calculation +,-,*,/

        double result;

        if (operator == '+') {
            result = num1 + num2;
            System.out.println("Result: " + result);
            
        } else if (operator == '-') {
            result = num1 - num2;
            System.out.println("Result: " + result);
            
        } else if (operator == '*') {
            result = num1 * num2;
            System.out.println("Result: " + result);
            
        } else if (operator == '/') {
            result = num1 / num2;
            System.out.println("Result: " + result);
            
        } else {
            System.out.println("Invalid operator! Please use + or -");
        }
    }
}
