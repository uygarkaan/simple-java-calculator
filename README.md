# Simple Java Calculator

This project is a basic Java calculator that prompts the user to input two numbers and then calculates and displays their sum. It's an introductory example for beginners to understand how to use the `Scanner` class for user input and perform basic arithmetic operations.

## Features

- Prompts the user to enter two integer values.
- Adds the two numbers and displays the result.
- Demonstrates the use of `Scanner` for reading user input.

## Code Breakdown

- **Scanner Initialization:** The `Scanner` object is created to read input from the user.
- **User Input:** Prompts the user to input two integers.
- **Addition Operation:** The program calculates the sum of the two integers.
- **Output:** Displays the result to the user.
- **Resource Management:** Closes the `Scanner` object to prevent resource leaks.

## Code

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter the first number:");
        int number1 = scanner.nextInt();

        System.out.println("Enter the second number:");
        int number2 = scanner.nextInt();

        int total = number1 + number2;

        System.out.println("Total: " + total);

        scanner.close();
    }
}
```

## Example Output
```

Enter the first number:
5
Enter the second number:
3
Total: 8

```
## Follow Me

#### Hello! I'm **Uygarcode**, a passionate software developer constantly exploring new innovations in technology and coding. I would be thrilled to have you join me on my coding journey!

#### You can find my coding projects, tech news, and personal updates on my social media accounts. Stay updated with my latest projects and follow the latest trends in the tech world through the links below: 

- #### **GitHub:** [github.com/uygarcode](https://github.com/uygarcode) - Explore my code projects, open-source contributions, and development journey!
- #### **LinkedIn:** [linkedin.com/in/uygarkaan](https://linkedin.com/in/uygarkaan) - Connect with me professionally and follow my career development.
- #### **Instagram:** [instagram.com/uygarcode](https://instagram.com/uygarcode) - Check out my personal updates, tech news, and more!
- #### **Discord:** [discord.gg/8v6SW9gnEt](https://discord.gg/8v6SW9gnEt) - Join our software community and engage in coding discussions!
