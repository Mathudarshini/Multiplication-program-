import java.util.Scanner;

public class MultiplicationProgram {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        // Ask the user for two numbers
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        // Multiply the two numbers
        int result = num1 * num2;

        // Display the result
        System.out.println("The result of " + num1 + " multiplied by " + num2 + " is: " + result);

        // Close the scanner
        scanner.close();
    }
    out put Enter the first number: 5
Enter the second number: 3
The result of 5 multiplied by 3 is: 15
}
# Multiplication-program-
