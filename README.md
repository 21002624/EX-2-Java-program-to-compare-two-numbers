# EX-2-Java-program-to-compare-two-numbers
```
import java.util.Scanner;

public class CompareNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the first number: ");
        double num1 = scanner.nextDouble();

        System.out.print("Enter the second number: ");
        double num2 = scanner.nextDouble();


        if (num1 > num2) {
            System.out.println(num1 + " is greater than " + num2);
        } else if (num1 < num2) {
            System.out.println(num1 + " is less than " + num2);
        } else {
            System.out.println(num1 + " is equal to " + num2);
        }

        scanner.close();
    }
}

```

# Output
![Screenshot (66)](https://github.com/21002624/EX-2-Java-program-to-compare-two-numbers/assets/113762183/5cb9a4ba-1b05-428f-b7dd-1d2848ebc29e)
