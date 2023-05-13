# Experiment-1

# Arithmetic Operations

## Aim:
  To write a Java program to perform arithmetic operations on the given numbers.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it ArithmeticOperations.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using arithmetic operations.

Step 5 : Display the operations done the input numbers in the terminal.

## Program
```
Developed by : K.Balaji
Register number : 212221230011
```
```
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the value of x");
        int x = sc.nextInt();
        System.out.println("Enter the value of y");
        int y = sc.nextInt();
        int add = x+y;
        System.out.println("Addition of x and y");
        System.out.println(add);
        int sub = x-y;
        System.out.println("Subtraction of x and y");
        System.out.println(sub);
        int mul = x*y;
        System.out.println("Multiplication of x and y");
        System.out.println(mul);
        int div = x/y;
        System.out.println("Division of x and y");
        System.out.println(div);
        int mod = x%y;
        System.out.println("Modulus of x and y");
        System.out.println(mod);
    }
}
```
## Output
![image](https://github.com/balaji-21005757/Ezperiment-1/assets/94372294/6a64272b-6625-4179-a37d-8f9bef8b069a)

## Result 
  We have successfully created a Java program to display the arithmetic operations on numbers.
