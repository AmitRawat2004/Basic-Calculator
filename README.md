# Basic-Calculator
This is my first repository of making calculator
<br>
Created by Amit Rawat(Owner).
<br>
*** Here are the code :-  ***
<br>
import java.util.*;
public class Table {
public static void main(String [] xyz) {
Scanner sc = new Scanner (System.in);
System.out.println("Enter your first number : ");
double num1 = sc.nextDouble();
System.out.println("Enter your second number : ");
double num2 = sc.nextDouble();
System.out.println("Enter your operator (+,-,*,/) : ");
char operator = sc.next().charAt(0);
double result;

        switch (operator) {
            case '+' -> result = num1 + num2;
            case '-' -> result = num1 - num2;
            case '*' -> result = num1 * num2;
            case '/' -> result = num1 / num2;
            default -> {
                System.out.println("Invalid operator");
                return;
            }
        }
        System.out.println("Result " + result);
    }
}