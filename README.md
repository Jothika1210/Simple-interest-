# Simple-interest-

CODING:
import java.util.Scanner;
public class SimpleInterestCalculator {
public static void main(String[] args) {
Scanner scanner = new Scanner(System.in);
System.out.print("Enter the principal amount: ");
double principal = scanner.nextDouble();
System.out.print("Enter the rate of interest (in %): ");
double rate = scanner.nextDouble();
System.out.print("Enter the time (in years): ");
double time = scanner.nextDouble();
double simpleInterest = (principal * rate * time) / 100;
System.out.println("The Simple Interest is: " + simpleInterest);
scanner.close();
}
}
OUTPUT:
Enter the principal amount: 1000
Enter the rate of interest (in %): 5
Enter the time (in years): 2
The Simple Interest is: 100.0
